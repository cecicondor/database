# database
teórico de banco de dados do terceiro semestre da faculdade de Ciência da Computação.


I - A princípio o que são banco de dados? Nada mais são de modo genérico coleção de dados relacionados, fatos que podem ser registrados e também possuem significado implícito além da sua representação com aspectos do mundo real. 

II - E suas aplicações? A plicação de dados tradicionais que armazena informações textuais ou numéricas. Temos a função de BD multimídia que é capaz de armazenar imagens, clipes de audio e stream de vídeo digitais.

III - Possui informações geográficas que analisa mapas, dados sobre o clima e imagens de satélite, já o sistema de data warehousing e de processamento analítico extrai a analisa informaçoes comerciais úteis de banco de dados muito grandes afim de também auxiliar na tomada de decisão, outra aplicação também é a de tecnologia de tempo real de banco de dados ativo que controla processos industriais e de manufatura. 

O PRIMEIRO BANCO DE DADOS teve início nas décadas de 60 e de 70 na IBM com pesquisas de automação de tarefas de escritório pois nessa época era necessário muita mão de obra o que simbolizava gasto, as pessoas precisavam fazer tarefas repetitivas de armazenar documentos. Ainda na década de 70 foi escrito um artigo sobre banco de dados relacionais e esse artigo dizia em questão da forma de consulta de banco de dados em tabelas. A IBM cirou um grupo de pesquisa chamado System R para desenvolver um sistema de banco de dados, pois o DB não foi enxergado de modo eficiente além de ser complexo demais para ser adquirido, dessa forma foi criado o STRUCTURED QUERY LANGUAGE (SQL). Belê, mas qual a diferença entre bancos de dados e sistemas de arquivos? Primeiramente vamos conhecer um pouco de ambos >

Alguns sistemas de arquivos são: NTFS / Ext2 / Ext3 / ReiserFs...
Banco de dados são: MySQL / FireBird / SQLServer / Oracle / DB2 , porém ambos têm objetivos em comum, mas suas distinções são notáveis quanto. Partindo da da finalidade e isso se mostra quanto a um sisterma de banco de dados avançado em gerenciar e armazenar grandes quantidades de dados além de possuírem um estrutura de dados mais complexa como tabelas, relações e índices. Banco de dados pode ser escalado horizontalmente adicionando mais servidores no sistema. A compartibilidade de dados em sistema de arquivos permite geralmente acesso de arquivo de usuário de uma única vez partindo assim no banco de dados podemos fazer isso de modo a deixarem que usuários utilizem e usufruam de seus servições de maneira simultânea. 
>>>>>>>>> Bancos de dados fornecem mecanismos para gerenciar o acesso simultâneo a dados por muitos usuários utilizando transações para garantir o sucesso das operações de dados para serem completados ou revertidos e também oferecem controle de concorrência para gerenciar conflitos de acessi a dadism dessa forma diferentemente de um arquivo excel na rede de uma empresa não teremos conflitos.

Vamos aos pontos mais altos do porquê banco de dados é benéfico partindo da rapidez no acesso a informações presentes no banco, reduz redundância e também de integridade, diminui esforço humano no desenvolvimento. 


IV - O que é um SGBD? É um conjunto de programnas que configuram e atualizam a mantém o banco de dados e nele vem recurso para administrar usuários e permissões, alterar tabelas e BDs, recurso para backup e restauração de dados além da ótima performance do banco, além de seguro oferece uma estruração dos dados com tabelas, colunas tipagem dos dados, chave primárias e estrangeiras, índices e etc. ORACLE / IBM / FIREBIRD / SYBASE / DB2 são alguns sistemas de gerenciamento de banco de dados. 

VI - Quais são as principais características de um banco de dados? 

- NATUREZA DE AUTODESCRIÇÃO que significa que o sistema de banco de dados contém definição completa de sua estrutura e restrições (metadados que que descreve a estrutura do banco de dados). 
- INDEPENDENCIA DE DADOS do programa de acesso do cliente, por estarem contidos no SGBD, a abstração de dados permite que a independencia dos dados do programa e independência da operação do programa.



Atualmente temos camadas de software que implementam a orientação a objetos no banco de dados relacional  = HIBERNATE / NHibernate / ADO Entity Framework. O XML (eXtended Markup Language) é considerado o principal padrão para intercâmbio entre diversos tipos de banco de dados e páginas na web.
