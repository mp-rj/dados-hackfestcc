# Dados úteis para o Hackfest Contra a Corrupção

Uma lista, não exaustiva mas útil, de dados que já usamos ou vimos que é viável usar em edições passadas do Hackfest Contra a Corrupção.

<!-- toc -->


- [Dados sobre combate a corrupção](https://github.com/mp-rj/dados-hackfestcc/blob/master/combate-a-corrupcao.md)
- [Dados sobre eleições realizadas](https://github.com/mp-rj/dados-hackfestcc/blob/master/eleicoes.md)
- [Dados sobre o Poder Legislativo](https://github.com/mp-rj/dados-hackfestcc/blob/master/legislativo.md)
- [Dados sobre orçamento, contratações e gastos públicos](https://github.com/mp-rj/dados-hackfestcc/blob/master/orcamento-publico.md)
- [Outros dados](https://github.com/mp-rj/dados-hackfestcc/blob/master/outros.md)
- [Cadastro de Empresas Inidôneas e Suspensas (CEIS)](#cadastro-de-empresas-inidôneas-e-suspensas-ceis)



[Prontos e já usados](#prontos-e-já-usados)
  * [Localização de empresas (CNPJ e CEP)](#localização-de-empresas-cnpj-e-cep)
  * [Presenças, votações e votos dos deputados federais na câmara](#presenças-votações-e-votos-dos-deputados-federais-na-câmara)
  * [Discursos dos deputados federais na câmara](#discursos-dos-deputados-federais-na-câmara)
  * [Gastos da Cota para Exercício da Atividade Parlamentar dos deputados federais](#gastos-da-cota-para-exercício-da-atividade-parlamentar-dos-deputados-federais)
  * [Candidatos, seus bens e as doações que eles receberam nas eleições de 2012, 2014 e 2016](#candidatos-seus-bens-e-as-doações-que-eles-receberam-nas-eleições-de-2012-2014-e-2016)
  * [SICONV: uso de verba do governo federal por municípios e estados (e universidades, institutos, ...) via convênios](#siconv-uso-de-verba-do-governo-federal-por-municípios-e-estados-e-universidades-institutos--via-convênios)


[Aparentemente prontos, mas não foram usados por nós](#aparentemente-prontos-mas-não-foram-usados-por-nós)
  * [Nuvem Cívica](#nuvem-cívica)
  * [Despesas – Transferências para Estados, Municípios ou entidades privadas – Portal da Transparência](#despesas--transferências-para-estados-municípios-ou-entidades-privadas--portal-da-transparência)
  * [Despesas – Gastos Diretos do Governo Federal – Portal da Transparência](#despesas--gastos-diretos-do-governo-federal--portal-da-transparência)
  * [Servidores Civis e Militares do Executivo Federal](#servidores-civis-e-militares-do-executivo-federal)
  * [Dirigentes de Empresas](#dirigentes-de-empresas)
  * [Transferências Programas Sociais Bolsa Família](#transferências-programas-sociais-bolsa-família)
  * [Pedidos e Respostas do e-SIC](#pedidos-e-respostas-do-e-sic)
  * [Webservice do e-OUV](#webservice-do-e-ouv)
  * [Relatórios da CGU](#relatórios-da-cgu)
  * [Dados sistematizados sobre parlamentares, seus gastos, parentes, empresas onde eles gastaram e discursos](#dados-sistematizados-sobre-parlamentares-seus-gastos-parentes-empresas-onde-eles-gastaram-e-discursos)
- [Contribua!](#contribuindo)

<!-- tocstop -->

---
---

## Prontos e já usados


### Presenças, votações e votos dos deputados federais na câmara
?    | ! |
 --- | --|
*O que é* | Dados das presenças, das propostas votadas e dos votos individuais dos deputados federais. |
*Formato* | Em xml através de uma API da câmara ou em csvs [neste repositório](https://github.com/nazareno/dados-da-camara-federal). |
*Dicas*   | Tem bastante dado a mais na API da câmara, inclusive discursos dos deputados. |
*Projetos usando* | [House of Cunha](http://www.houseofcunha.com.br)  |

---

### Discursos dos deputados federais na câmara
?    | ! |
 --- | --|
*O que é* | Dados dos discursos de nossos representantes da câmara. |
*Formato* | Em xml através de uma API da câmara |
*Url*     | [Na API de dados abertos da câmara](http://www2.camara.leg.br/transparencia/dados-abertos/dados-abertos-legislativo/webservices/sessoesreunioes-2/obterinteiroteordiscursosplenario) |
*Dicas*   | Às vezes os exemplos da API não funcionam tal qual estão na página, mas mudando um pouco dá certo.  |
*Projetos usando* | [Retórica Parlamentar](http://retorica.labhackercd.net/), [Matéria do NEXO](http://cidadania20.com/projectos/deputados-federais-em-plenario/) |

---

### Gastos da Cota para Exercício da Atividade Parlamentar dos deputados federais
?    | ! |
 --- | --|
*O que é* | Cada deputado tem cerca de R$50 mil / mês para gastar em sua atividade parlamentar. A câmara abriu os dados de todos esses gastos para que a população fiscalize. |
*Formato* | A câmara disponibiliza arquivos XML, JSON, CSV e XLSX compactados para download contendo os dados relativos aos gastos parlamentares registrados na Câmara dos Deputados. |
*Url*     | Direto no [site da câmara](http://www2.camara.leg.br/transparencia/cota-para-exercicio-da-atividade-parlamentar/dados-abertos-cota-parlamentar) |
*Dicas*   | Tem bastante dado a mais na API da câmara, inclusive discursos dos deputados. |
*Projetos usando* | [House of Cunha](http://www.houseofcunha.com.br), [Serenata de Amor](http://serenatadeamor.org) |

---

### Candidatos, seus bens e as doações que eles receberam nas eleições de 2012, 2014 e 2016
?    | !  |
 --- | -- |
*O que é* | Detalhes demográficos, de bens, doações e gastos dos candidatos de 2016 e das eleições anteriores |
*Formato* | CSV |
*Url*     | http://www.tse.jus.br/hotSites/pesquisas-eleitorais/candidatos_anos/2016.html  |
*Dicas*   | Há um dicionário dos dados em pdf. O formato mudou um pouco ao longo dos anos, mas eles procuram manter a compatibilidade. Não é simples cruzar os nomes dos candidatos com os dos parlamentares na API da câmara.  |
*Projetos usando* | [De onde vem o dinheiro nas eleições de 2016?](https://nazareno.shinyapps.io/minha-cidade/), [Nossos vereadores, Campina Grande](http://www.vereadorescg.cc) |

---

### SICONV: uso de verba do governo federal por municípios e estados (e universidades, institutos, ...) via convênios
?    | !  |
 --- | -- |
*O que é* | Boa parte das obras estruturantes e grandes serviços dos municípios e estados é feito com verba federal obtida via convênios. O SICONV tem dados abertos detalhados sobre os convênios celebrados, licitações e pagamentos envolvidos, se a prestação de contas foi aceita ou houve problema, e o cronograma disso tudo. Tem também informação dizendo se a verba do convênio é resultante de uma emenda parlamentar de um deputado federal ou senador. |
*Formato* | CSVs |
*Url*     | http://portal.convenios.gov.br/download-de-dados  |
*Dicas*   | Há um MER na página. Os csvs são atualizados diariamente. Esses csvs são mais completos que a API de convênios. Prestação de contas rejeitada é sinal de que o convênio não foi executado corretamente. Deputados alocam verbas via emendas parlamentares que acabam sendo executadas como convênios. |
*Projetos usando* | [As Diferentonas](https://github.com/nazareno/diferentonas-server/), [Na emenda dos deputados](https://github.com/CelioBarros/NaEmendaDeputado), Quase todos [os apps que participaram do hackathon do MJ](https://github.com/LabPi) |

---

## Aparentemente prontos, mas não foram usados por nós

### Nuvem Cívica
?    | ! |
 --- | --|
*O que é* | API de acesso para diversas fontes de dados abertos governamentais.|
*Formato* | API REST (json) |
*Url*     | https://github.com/AppCivicoPlataforma/AppCivico |
*Dicas*   | Tem informações georreferênciadas sobre escolas e estabelecimentos de saúde públicos/privados do país (coletados através do DATA SUS e INEP). Há tembém informações sobre os remédios fabricados no Brasil (ANVISA). Além disso, há API para consulta de postos do Site Nacional de Empregos (SINE)|
*Projetos usando* |  |

---

### Despesas – Transferências para Estados, Municípios ou entidades privadas – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Transferências de recursos federais, constitucionais, legais ou voluntárias, para estados, municípios, Distrito Federal, instituições privadas com e sem fins lucrativos e ao exterior, realizados pelos órgãos e entidades da Administração Pública Federal, que executam as despesas pelo Sistema Integrado de Administração Financeira do Governo Federal (Siafi). |
*Formato* | CSV |
*Url*     | http://www.portaltransparencia.gov.br/downloads/mensal.asp?c=Transferencias#meses04|
*Dicas*   | Dados atualizados mensalmente.   |
*Projetos usando* | Para onde foi o meu dinheiro? |

---

### Despesas – Gastos Diretos do Governo Federal – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Pagamentos para aquisição e contratação de obras e compras governamentais, dentre outros, realizados pelos órgãos e entidades da Administração Pública Federal, que executam as despesas pelo Sistema Integrado de Administração Financeira do Governo Federal (Siafi). Dados disponibilizados no Portal da Transparência |
*Formato* | CSV |
*Url*     | http://www.portaltransparencia.gov.br/downloads/mensal.asp?c=GastosDiretos |
*Dicas*   | Dados atualizados mensalmente.   |
*Projetos usando* | Para onde foi o meu dinheiro? |

---

### Servidores Civis e Militares do Executivo Federal
?    | ! |
 --- | --|
*O que é* | Informações sobre cargo, função, situação funcional e remuneração dos servidores civis e militares, bem como dos agentes públicos do Poder Executivo Federal. |
*Formato* | CSV |
*Url*     | http://www.portaltransparencia.gov.br/downloads/servidores.asp |
*Dicas*   | Atualização mensal |
*Projetos usando* |  |

---

### Dirigentes de Empresas
?    | ! |
 --- | --|
*O que é* | Informações sobre ocupantes de cargos de gerência e direção em empresas estatais e subsidiárias. |
*Formato* | CSV |
*Url*     | http://www.portaldatransparencia.gov.br/downloads/snapshot.asp?c=Dirigentes |
*Dicas*   | Atualização mensal |
*Projetos usando* |  |

---

### Transferências Programas Sociais Bolsa Família
?    | ! |
 --- | --|
*O que é* | Informações sobre as transferências de recursos federais diretamente repassados a cidadãos, referentes ao pagamento do Bolsa Família, realizadas pelo Ministério do Desenvolvimento Social, por meio da Caixa Econômica Federal. |
*Formato* | CSV |
*Url*     | http://www.portaldatransparencia.gov.br/downloads/mensal.asp?c=BolsaFamiliaFolhaPagamento |
*Dicas*   | Atualização mensal |
*Projetos usando* |  |

---

### Pedidos e Respostas do e-SIC
?    | ! |
 --- | --|
*O que é* | Base de dados dos pedidos e respostas realizados no Poder Executivo Federal, por meio do e-SIC, com base na Lei de Acesso à Informação.|
*Formato* | CSV e XML |
*Url*     | http://www.consultaesic.cgu.gov.br/busca/_layouts/15/DownloadPedidos/DownloadDados.aspx |
*Dicas*   | O arquivo Pedidos contém dados sobre as solicitações, incluindo o conteúdo dos pedidos e respostas. Já o arquivo Recursos fornece o conteúdo, dentre outros dados, dos recursos apresentados pelo solicitante quando ele entende que não foram concedidas a informação ou o motivo para a negativa. O arquivo solicitante fornece informações individualizadas, exceto nome, sobre os autores dos pedidos. Atualização diária |
*Projetos usando* | Achados e Pedidos |

---

### Webservice do e-OUV
?    | ! |
 --- | --|
*O que é* |Webservice para registro e consulta de manifestações de ouvidoria (denúncias, reclamações, sugestões etc.) direcionadas às ouvidorias do governo federal, incluindo a Ouvidoria-Geral da União da CGU.|
*Formato* | |
*Url*     | [Neste link](etc/e-ouv---documentacao-webservices.docx) |
*Dicas*   |O documento disponível no link acima explica como acessar os serviços e conectar seu aplicativo ao e-OUV. Por meio do serviço, um aplicativo para detectar irregularidades em obras federais pode, por exemplo, registrar diretamente uma denúncia para a CGU. Importante: o e-OUV permite o registro apenas de manifestações para órgãos do Poder Executivo Federal. Assim, se a obra ou serviço for realizado apenas com recursos estaduais, por exemplo, a denúncia deve ser encaminhada a órgãos estaduais como ouvidoria do Governo do Estado, Tribunal de Contas ou Ministério Público estadual.|
*Projetos usando* | Reclame Aqui |

---

### Relatórios da CGU
?    | ! |
 --- | --|
*O que é* | Relatórios de fiscalização em estados e municípios, auditorias anuais de contas de órgãos federais, avaliações de programas federais, entre outros. |
*Formato* |PDF |
*Url*     | http://auditoria.cgu.gov.br/public/relatorio/consultar.jsf?windowId=9db |
*Dicas*   |É possível baixar um ou mais arquivos ou exportar a lista de resultados em formato csv. |
*Projetos usando* | |

---

### Cadastro de Empresas Inidôneas e Suspensas (CEIS)
?    | ! |
 --- | --|
*O que é* | Empresas e pessoas físicas que sofreram sanções pelos órgãos e entidades da administração pública das diversas esferas federativas. |
*Formato* | csv |
*Url*     | http://www.portaldatransparencia.gov.br/downloads/snapshot.asp?c=CEIS |
*Dicas*   |  |
*Projetos usando* |  |

---

### Dados sistematizados sobre parlamentares, seus gastos, parentes, empresas onde eles gastaram e discursos
?    | ! |
 --- | --|
*O que é* | Dados da câmara e de outras fontes, incluindo geolocalização das empresas onde parlamentares gastaram, seus parentes, seus assessores e mais coisa que parece bem legal, sistematizado pelo pessoal da Operação Serenata de Amor  |
*Formato* | csvs compactados como xz  |
*Url*     | https://github.com/datasciencebr/serenata-toolbox/ , também temos os dados no evento no hd externo chamado nuvem |
*Dicas*   |   |
*Projetos usando* | https://serenatadeamor.org |

---


## Contribuindo

Adoramos contribuições. Para adicionar um novo dado, copie o template abaixo, edite a seção e mande um pull request.

```
### Título
     ?    | ! |
      --- | --|
*O que é* |   |
*Formato* |   |
*Url*     |   |
*Dicas*   |   |
*Projetos usando* |  |
```
