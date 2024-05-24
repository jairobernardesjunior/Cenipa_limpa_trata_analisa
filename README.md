# Cenipa_limpa_trata_armazena

![Imagem de Aviao](https://github.com/jairobernardesjunior/Cenipa_limpa_trata_analisa/blob/main/aviao_b.jpg)
 
## Monta Base Analítica de Acidentes Aeronáuticos para Estudos

Dados de ocorrências aeronáuticas da aviação civil brasileira.
- https://dados.gov.br/dados/conjuntos-dados/ocorrencias-aeronauticas-da-aviacao-civil-brasileira

Opendata AIG Brazil
A base de dados de ocorrências aeronáuticas contém os dados sobre as aeronaves envolvidas, fatalidades, local, data, horário dos eventos e informações taxonômicas típicas das investigações de acidentes (AIG). São resguardadas a privacidade de pessoas físicas/jurídicas envolvidas conforme previsto pela Lei de Acesso à Informação (Lei n° 12.527, de 18 de novembro de 2011).

Essa base de dados é composta por informações preliminares provenientes do formulário CENIPA-05 (Ficha de Notificação de Ocorrências Aeronáuticas) e consolidada a partir dos relatórios de investigações publicados. Outra forma de visualização desses dados é pelo [__*Painel SIPAER*__](https://painelsipaer.cenipa.fab.mil.br/QvAJAXZfc/opendoc.htm?document=SIGAER%2Fgia%2Fqvw%2Fpainel_sipaer.qvw&host=QVS%40cirros31-37&anonymous=true) disponível na página do CENIPA.

Tabelas (arquivos)
- OCORRÊNCIA.csv - Informações sobre as ocorrências.
- OCORRÊNCIA_TIPO.csv - Informações sobre o tipo de ocorrência.
- AERONAVE.csv - Informações sobre as aeronaves envolvidas nas ocorrências.
- FATOR_CONTRIBUINTE.csv - Informações sobre os fatores contribuinte das ocorrências que tiveram investigações finalizadas.
- RECOMENDAÇÃO.csv - Informações sobre as recomendações de segurança geradas nas ocorrências.

Este projeto visa acessar as bases de dados de acidentes aeronáuticos do cenipa, fazer a limpeza e o tratamento dos dados, selecionar as colunas dos dados relevantes para pesquisa, deixando uma base analítica única para servir de estudo para outros projetos.
