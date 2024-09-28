# Page View Time Series Visualizer

This is the boilerplate for the Page View Time Series Visualizer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/page-view-time-series-visualizer



Use os dados para completar as seguintes tarefas:

    Use o Pandas para importar os dados do arquivo "fcc-forum-pageviews.csv". Defina o índice para a coluna de data.
    
    Limpe os dados filtrando os dias em que as visualizações de página estavam no top 2,5% ou no bottom 2,5% do conjunto de dados.
    
    Crie uma função draw_line_plot que use o Matplotlib para desenhar um gráfico de linha semelhante a "examples/Figure_1.png". O título deve ser Daily freeCodeCamp Forum Page Views 5/2016-12/2019. O rótulo no eixo x deve ser Date e no eixo y deve ser Page Views.

    Crie uma função draw_bar_plot que desenhe um gráfico de barras semelhante a "examples/Figure_2.png". Ele deve mostrar a média de visualizações diárias de páginas para cada mês, agrupadas por ano. A legenda deve exibir os nomes dos meses e ter o título Months. No gráfico, o rótulo no eixo x deve ser Years e o rótulo no eixo y deve ser Average Page Views.
    
    Crie uma função draw_box_plot que use o Seaborn para desenhar dois gráficos de caixa adjacentes, semelhantes a "examples/Figure_3.png". 
    Esses gráficos devem mostrar como os valores são distribuídos dentro de um determinado ano ou mês e como isso se compara ao longo do tempo. 
    O título do primeiro gráfico deve ser Year-wise Box Plot (Trend) e o título do segundo gráfico deve ser Month-wise Box Plot (Seasonality). 
    Certifique-se de que os rótulos dos meses no eixo inferior comecem em Jan e que os eixos x e y estejam corretamente rotulados. O código fornecido já inclui comandos para preparar os dados.

Para cada gráfico, certifique-se de usar uma cópia do DataFrame.

O código boilerplate também inclui comandos para salvar e retornar a imagem.
