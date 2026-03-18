# projeto
projeto imdb_movies

utilizando o powerbi, e utilizando o powerquery e tratando os dados.

ETL (Power Query)
As principais transformações realizadas foram:
Renomeação da tabela para imdb_movies
Promoção de cabeçalhos
Remoção de colunas desnecessárias (ex: link)
Remoção de duplicatas com base no ID
Tradução dos nomes das colunas para português
Ajuste dos tipos de dados (ano, orçamento, faturamento)
Padronização dos títulos para letras maiúsculas
Tratamento da coluna de gêneros (mantendo apenas o primeiro)
Remoção de valores nulos na nota IMDB
Conversão da duração para minutos totais
Tratamento de valores vazios como null

Dashboard
O dashboard foi desenvolvido para responder às perguntas de negócio e inclui:
Gráfico de barras com os gêneros mais lucrativos
Indicadores (cards) com:
Total de filmes
Média de nota IMDB
Resultado financeiro total
Filtros interativos (ano, gênero, etc.)
