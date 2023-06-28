**História: A Odisseia da Empresa Z em busca de Análises Otimizadas**

Era uma vez, em uma empresa chamada Z, que vivia no mundo dos negócios, enfrentava uma grande adversidade: problemas de lentidão em seus relatórios e dashboards. Os analistas de dados da Empresa Z lutavam para realizar análises eficientes e obter insights valiosos a partir dos dados. 

A causa raiz dessa lentidão foi identificada: a tabela `tbestoque` era a origem de dados para todas as análises realizadas na empresa. Essa tabela continha informações importantes sobre produtos, fornecedores e lojas, mas sua estrutura desorganizada e a falta de otimização estavam prejudicando a performance das análises.

Se depararam com um verdadeiro desafio. Os relatórios e dashboards que deveriam fornecer informações rápidas e precisas aos gestores estavam demorando uma eternidade para serem carregados. A equipe sentia que estavam perdendo batalhas importantes no mundo competitivo dos negócios.

Determinados a superar esse obstáculo e alcançar um novo patamar de excelência, a diretoria da Empresa Z decidiu buscar uma consultoria especializada em análise de dados. Eles estão em busca de profissionais capacitados que possam ajudá-los a reverter essa situação, propor insights estratégicos e implementar soluções eficientes. A diretoria está comprometida em investir nos recursos necessários para transformar os desafios atuais em oportunidades de crescimento e sucesso.

Abaixo o caminho com a base de dados do cliente.
- [Download]()


A tabela em questão tem a seguinte estrutura:

```sql
CREATE TABLE tbestoque (
   produto_id SERIAL PRIMARY KEY,
   nome_produto VARCHAR(100),
   categoria_produto VARCHAR(50),
   preco_produto NUMERIC(10,2),
   fornecedor_id SERIAL,
   nome_fornecedor VARCHAR(100),
   endereco_fornecedor VARCHAR(200),
   telefone_fornecedor VARCHAR(20),
   loja_id SERIAL,
   nome_loja VARCHAR(100),
   endereco_loja VARCHAR(200),
   cidade_loja VARCHAR(100),
   quantidade_estoque INT,
   data_estoque DATE
);
```
ss