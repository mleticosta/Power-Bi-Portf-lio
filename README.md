# Power-Bi-Portfolio

# Dashboard de Vendas

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNWEzYTNjMDMtYzRjOC00ZTEzLWI2MjUtN2M1Mzk5YmMwNmUxIiwidCI6IjM0MTliNDQyLTMzN2ItNGY5ZS1iODZmLTVhNTY2MDNiNDZhZiJ9


## Sugestão de Leitura

Para facilitar a compreensão, recomendo acessar o dashboard através do link acima e, enquanto lê o texto, visualizar os elementos mencionados. Caso prefira, incluí algumas imagens abaixo para referência. Agradeço pelo seu tempo e desejo uma ótima leitura!


## Problema

O principal objetivo desta análise e da construção do dashboard foi compreender o faturamento da empresa no ano de 2020.

Com o objetivo definido, foram criadas subdivisões para detalhar o faturamento em diferentes perspectivas: por estado, por cidade, por produto, além de períodos específicos, como trimestre, mês e dia.

Adicionalmente, foi incorporado um filtro por produto, permitindo uma análise mais direcionada e facilitando a comparação entre diferentes categorias.


### Etapas do processo

1) Carregamento dos Dados: Os dados foram importados para o Power BI, estabelecendo a base inicial para a construção do dashboard.

2) Verificação e Limpeza dos Dados: Utilizando o Power Query, foi realizada uma análise preliminar das tabelas para identificar possíveis dados ausentes ou inconsistências.

3) Separação de Localização: A coluna de localização foi desmembrada, originando duas novas colunas: Cidade e Estado.

4) Criação da Coluna de Faturamento: Foi utilizado o recurso DAX (Data Analysis Expressions) para calcular e criar a coluna referente ao faturamento.

5) Criação de Novas Medidas: Foram desenvolvidas medidas adicionais para organizar os dados e simplificar a construção do dashboard.

6) Medidas Desenvolvidas: Foram criadas as seguintes medidas principais através do "DAX":

Faturamento Total: SUM(Vendas[Faturamento])
Quantidade Total de Itens Vendidos: SUM(Vendas[Qtd Vendida])
Quantidade Total de Vendas: COUNTROWS(Vendas)
Visualização de Indicadores Totais: Todas as medidas foram apresentadas no visual "Cartão", permitindo ao usuário visualizar os valores totais anuais de maneira clara e direta.

7) Seleção de Gráficos: Foram avaliados e implementados os gráficos mais adequados para representar as variáveis relacionadas ao faturamento. Cada gráfico foi acompanhado de títulos explicativos para contextualizar os dados analisados.

8) Filtro por Produto: Foi adicionado um filtro para permitir a segmentação por categoria de produto, possibilitando análises mais específicas e direcionadas.

9) Finalização do Dashboard: Após a conclusão do projeto, o dashboard foi disponibilizado para consulta (acessível pelo link no início da página).
  

# Dashboard Final (Power BI Service)

![dashboard_snapo](https://github.com/user-attachments/assets/c33a575b-a843-4fd3-9843-b9abd983d5b3)

 
# Insights

As seguintes inferências podem ser extraídas do painel:

### [1] Total do Faturamento Anual: 99 Milhões

   Maior Estado com Faturamento: São Paulo - 32 Milhões       
   
![grafico_estado](https://github.com/user-attachments/assets/f9597b70-d08f-47a9-93fc-3b7be832e665)


   Maior Cidade com Faturamento: São Paulo Capital - 16 Milhões

![grafico_cidade](https://github.com/user-attachments/assets/9afdbc2f-7789-4d94-81ad-86dddb31be67)


   O Produto com Maior Faturamento: Iphone
   
![grafico_produto](https://github.com/user-attachments/assets/6c2fef7c-ad73-4bae-be5b-945272857351)


   O Trimestre que mais vendeu: o último - 4º Qtr
   
![grafico_trimestre](https://github.com/user-attachments/assets/ca9c77ac-b7d2-4420-beac-de9d93dfea11)



   - A análise permitiu identificar produtos com desempenho abaixo do esperado nas vendas, bem como os estados com menor representatividade no volume total de vendas. Com base nessas informações, é possível desenvolver estratégias direcionadas para potencializar o desempenho dos produtos e regiões de baixo rendimento, ao mesmo tempo em que se busca manter a excelência nas áreas e itens que já apresentam resultados satisfatórios.
