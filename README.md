# Desafio MK 

Desafio com o intuito de manipular arquivos csv usando Python.

## Descrição

Listar as top 100 faixas seguindo o critério de que a melhor faixa foi aquela que ficou mais semanas no billboard charts.

Saída 1: <br />
top100faixas.csv  <br />
Com as colunas  <br />
Rank,Song,Artist,Peak Position,Weeks in Charts


Listar os top 10 artistas que começam com a letra "P", seguindo o seguinte critério de pontuação: Cada música do artista que fica por 1 semana no billboard charts dá 1 ponto para esse artista.
Por exemplo, o artista Prodigy tem 3 músicas na base de dados, H-N-I-C = 15 semanas, Return Of The Mac = 3 semanas,H.N.I.C. Pt. 2 = 2 semanas. Nesse critério Prodigy tem 20 pontos.

Saída 2:  <br />
top10artistas_p.csv  <br />
Com as colunas  <br />
Rank,Artist,Pontos


## Resolução

O desafio foi feito com Python, utilizando o Jupyter Notebook , que  é uma aplicação web de código aberto que permite criar e compartilhar documentos que contêm código interativo,
visualizações, texto explicativo e equações matemáticas. Para análise dos dados, utilizei a biblioteca Pandas, onde pude fazer todas as alterações exigidas.

Para instalar o pandas rode o comando ( com o venv já instalado )

```
pip install pandas
```
- Dentro dos arquivos csv , está o resultado das saídas.
