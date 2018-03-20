# Votacao-Marielle
Análise da votação da vereadora Marielle Franco (PSOL) nos bairros do Rio.

Este notebook analisa os dados de votação em Franco por zona eleitoral do município. A base de dados está disponível no repositório de dados eleitorais do TSE (Tribunal Superior Eleioral). É possível baixá-la neste link: http://agencia.tse.jus.br/estatistica/sead/odsele/votacao_partido_munzona/votacao_partido_munzona_2014.zip

Antes de iniciar a análise por zona em Python, filtrei os resultados da vereadora na eleição municipal de 2016, cruzando as zonas eleiorais com os bairros. A relação entre cada zona e seus bairros está disponível nesta tabela: http://www.tre-rj.gov.br/site/eleicoes/2016/arquivos/porBairroZon.xls

Contei com a ajuda do Fernando Masanori (https://github.com/fmasanori), que desenvolveu um código em Python para agregar todas os bairros de uma zona eleitoral em uma única célula.

O resultado deste cruzamento inicial está neste link: https://docs.google.com/spreadsheets/d/1Rph2NxHFJhg8SZuTBV4AmdqkuL8EdyaJQ76w2fdBrwo/edit?usp=sharing\

Nele, é possível ver os bairros em que Marielle obteve votação mais expressiva.

A partir de então, voltei à base de dados do TSE, previamente filtrada no Excel para deixar apenas os dados de candidatos a vereador no município do Rio de Janeiro.

A análise a seguir verifica (1) quais foram os candidatos a vereador mais votados na Maré e nas zonas em seu entorno. Marielle nasceu no complexo da Maré nasceu e representava politicamente essa região. Também observa (2) quais foram os candidatos a vereador mais votados nos bairros em que a vereadora teve seu melhor desempenho.

