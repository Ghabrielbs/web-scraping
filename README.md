Este projeto é um script Python que consome dados da API (não oficial) do Sofascore para analisar e comparar estatísticas de desempenho de times do futebol brasileiro (Séries A e B) ao longo das temporadas de 2017 a 2022.
O script permite que o usuário escolha dois times e uma métrica específica (ex: 'goalsScored'), e então gera um gráfico de barras interativo comparando o desempenho desses times ano a ano.

 Funcionalidades Principais
Extração de Dados: Conecta-se à API do Sofascore para buscar estatísticas detalhadas por time e por temporada.

Processamento com Pandas: Utiliza a biblioteca pandas para estruturar os dados JSON recebidos em um DataFrame limpo e organizado.

Visualização Interativa: Usa a biblioteca plotly para criar gráficos de barra interativos, permitindo comparações visuais claras.

Interface Simples: Solicita ao usuário a divisão (Série A ou B) de cada time via terminal (input) para construir as URLs de API corretas.

Análise Histórica: Os dados cobrem as temporadas de 2017 a 2022, permitindo uma análise da evolução ou queda de desempenho.

 Tecnologias Utilizadas
Python

Requests: Para realizar as chamadas HTTP para a API do Sofascore.

Pandas: Para manipulação, limpeza e agregação dos dados.

Plotly: Para a criação dos gráficos interativos.
