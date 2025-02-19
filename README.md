# Classificação ABC para Otimização de Estoque: Redução de Custos e Tomada de Decisão Estratégica
Projeto de classificação ABC utilizando Python, focado em resolver um dos maiores desafios de empresas médias e grandes: a gestão eficiente de estoque. O objetivo? Reduzir custos de armazenagem em 20% e evitar rupturas de produtos críticos, garantindo que recursos sejam alocados de forma inteligente.

# O Problema
A empresa fictícia GlobalMart (varejo de produtos de escritório, móveis e tecnologia) enfrentava custos elevados devido a estoques excessivos de itens de baixo giro e dificuldade em priorizar reposições. Em grandes empresas, estoques mal gerenciados podem gerar até 30% de desperdício financeiro (segundo o Council of Supply Chain Management Professionals).

# A Solução: Classificação ABC
A classificação ABC categoriza produtos com base em seu impacto financeiro:
  •	Categoria A: 15% dos produtos → 78% do valor de vendas (alta prioridade).
  •	Categoria B: 25% dos produtos → 17% do valor (atenção moderada).
  •	Categoria C: 60% dos produtos → 5% do valor (baixa prioridade).

Utilizei dados históricos de vendas (2014–2018) com campos como Sales, Quantity e Profit para calcular o valor acumulado de cada item e aplicar a regra 80/20 (Curva de Pareto).

![PARETO](https://github.com/user-attachments/assets/b0e69d5e-66c1-4e9d-a99b-fad16a7f7e06)


# Metodologia e Ferramentas
1.	Python e Pandas:
  Coleta e transformação de dados.
	Cálculo do valor total por produto e porcentagem acumulada.
	Classificação automática com função personalizada.
2.	Visualização de Dados (Matplotlib):
  Gráfico comparativo de produtos vs. vendas por categoria.
  Curva de Pareto para validação visual da distribuição.
3.	Lógica de Negócio:
  Regras claras para priorização (ex: produtos A demandam reposição frequente; C exigem revisão de giro).

# Resultados e Impacto
•	Redução de custos: Foco na redução de itens de baixo giro (Categoria C).
•	Evitar rupturas: Garantia de disponibilidade de produtos críticos (Categoria A).
•	Decisão estratégica: Insights para compras, negociação com fornecedores e alocação de espaço físico.

# Habilidades Aplicadas
•	Análise de Dados: Manipulação de datasets complexos e aplicação de métricas financeiras.
•	Programação em Python: Automação de classificação e geração de relatórios dinâmicos.
•	Visualização Técnica: Criação de gráficos claros para comunicação com stakeholders.
•	Gestão de Estoques: Tradução de teoria (regra 80/20) em soluções práticas escaláveis.

# Por Que Isso Importa?

  Para empresas de médio e grande porte, testar metodologias como a ABC não é opcional — é estratégico. Além de otimizar custos, essa abordagem      oferece clareza para decisões baseadas em dados, crucial em um mercado competitivo.

# Habilidades-chave destacadas: 
  Python, Pandas, Matplotlib, Análise Paretiana, Gestão de Estoques.
  Fique à vontade para comentar ou conectar-se para discutir como a classificação ABC pode transformar a gestão do seu negócio!
