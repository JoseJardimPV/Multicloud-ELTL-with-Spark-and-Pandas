# Projeto Final Engenharia de Dados SoulCode 

Repositório para entrega do projeto final do Bootcamp de Engenharia de Dados da SoulCode (ED7)  

## Equipe

* Ana Flavia Dias [(github)](github.com/anafla7)
* Ariana Caetano [(github)](github.com/ariana-caetano)
* Erika Cunha [(github)](github.com/Erikacunha024)
* José Jardim [(github)](github.com/JoseJardimPV)
* Marcos Valente [(github)](github.com/MarcosVCS)


### RESUMO DO TRABALHO

Dentre nossas instruções, deveríamos:
* Escolher duas bases de dados diferentes (sendo uma obritariamente em CSV e outra em formato diferente);
* Realizar processo completo de ETL dessas bases de dados (utilizando Python, Pandas, PySpark, SQL e ferramentas diversas da Google Cloud);
* Criar dashboard com insights a partir dos dados normalizados.

[Clique aqui para acessar requisitos elencados pelos professores](https://github.com/MarcosVCS/Projeto-Final---Engenharia-de-Dados---SoulCode/blob/main/Recursos%20README/Requisitos_trabalho.md)

Nosso grupo deveria trabalhar com o tema "COMÉRCIO - BRASIL", razão pela qual escolhemos bases de dados sobre comércio exterior (importação e exportação) e sobre comércio de combustíveis nos municípios brasileiros. Nosso objetivo foi colher insights a respeito do comércio de petróleo e combustível derivados, com base nos comércios externo e interno desses bens. Filtramos os dados disponíveis entre 2013 - 2022 (janela temporal de dez anos).


### DATASETS

Estatísticas de Comércio Exterior em Dados Abertos (COMEX STAT)
- Ministério da Economia
- 4 datasets (totalizando 56,929,067 linhas), com referências a 16 tabelas de Correlações de Códigos e Classificações.
- Disponíveis em: www.gov.br/produtividade-e-comercio-exterior/pt-br/assuntos/comercio-exterior/estatisticas/base-de-dados-bruta (Acesso em 3 de janeiro de 2022)

Preços de Revenda e de Distribuição de Combustíveis (ANP)
- Levantamento por municípios (semanal)
- 3 datasets (totalizando 1.190.920 linhas)
- Disponíveis em: www.gov.br/anp/pt-br/assuntos/precos-e-defesa-da-concorrencia/precos/precos-revenda-e-de-distribuicao-combustiveis/serie-historica-do-levantamento-de-precos (Acesso em 4 de janeiro de 2022)

Vendas de derivados de petróleo e biocombustíveis (ANP)
- Vendas de combustíveis por segmento (metros cúbicos) 2012-2022 
- Vendas de GLP por tipo de vasilhame (metros cúbicos) 2007-2022 
- Vendas de óleo diesel por tipo (metros cúbicos) 2013-2022
- Datasets totalizam 9.440 linhas
- Disponíveis em: https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/vendas-de-derivados-de-petroleo-e-biocombustiveis (Acesso em 6 de janeiro de 2022)


### WORKFLOW | TECNOLOGIAS UTILIZADAS

![Workflow](https://github.com/MarcosVCS/Projeto-Final---Engenharia-de-Dados---SoulCode/blob/main/Recursos%20README/Workflow.png?raw=true)
