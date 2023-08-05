# Storytelling: Criando um Banco de Marketing com PostgreSQL

Era uma vez, uma empresa chamada "**MKT Wizards**" que desejava melhorar sua compreensão dos clientes e a eficácia de suas campanhas. Para isso, eles decidiram criar um banco de dados para armazenar informações sobre seus clientes e suas compras. Mas como fazer isso da melhor forma possível?

## Fase 1: Preparação
Alex Souza e sua equipe começaram criando um novo banco de dados, que chamaram de *db_marketing*. Essa seria a base de todo o projeto. Com entusiasmo, eles começaram a imaginar como seria a estrutura do banco.

## Fase 2: Projetando as Tabelas
"Para começar", disse Alex Souza, "precisamos criar a tabela clientes. Vamos incluir campos como `id_cliente`, `nome`, `email`, `telefone` e `data_nascimento`." Cada membro da equipe contribuiu com ideias para garantir que a tabela atendesse às necessidades da empresa.

Mas a equipe sabia que uma única tabela não seria suficiente. Eles precisavam rastrear as compras de cada cliente. Então, decidiram criar outra tabela chamada compras. Essa tabela teria campos como `id_compra`, `id_cliente`, `produto` (descrição do produto), `valor` e `data_compra`. Agora eles estavam preparados para armazenar as informações necessárias.

**Não esquecer de Criar a modelagem conceitual e lógica.**

## Fase 3: Inserindo os Dados
Com as tabelas criadas, era hora de inserir os dados de exemplo. Alex Souza e sua equipe criaram **5 registros de clientes**, adicionando seus nomes, e-mails, telefones e datas de nascimento. Eles deram vida a esses clientes fictícios com informações detalhadas.

Mas o trabalho não parou por aí. A equipe queria enriquecer o banco de dados com compras aleatórias. Eles escreveram uma consulta SQL para criar **15 registros** de compras com valores variados, relacionando-os aos clientes existentes. Agora o banco de marketing estava repleto de informações valiosas!

## Fase 4: Explorando os Dados
Alex Souza e sua equipe ficaram animados para explorar o que haviam criado. Eles começaram com consultas simples, *obtendo os nomes e e-mails de todos os clientes*. Em seguida, descobriram *quais produtos cada cliente havia comprado e calcularam o valor total gasto por alguns clientes específicos*.

Também encontraram um jeito de viajar no tempo! Com uma consulta mágica, descobriram quais clientes haviam feito compras em *um dia específico*, trazendo informações úteis para analisar a eficácia de suas campanhas ao longo do tempo.

## Fase 5: Exportando Resultados
A equipe da **MKT Wizards** exportou as duas tabelas para um arquivo `.csv` (outros conectaram direto no bd), pois iriam fazer um teste com o **Pentaho**.

## Fase 6: No Pentaho
Montar uma **Modelagem Dimensional** e exportar as 3 tabelas para `3 arquivos .xlsx`.

## Bons estudos!
