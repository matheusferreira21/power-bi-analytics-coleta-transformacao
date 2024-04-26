# Segundo desafio de projeto do bootcamp Power BI Analytics
## Objetivo
Fazer a coleta de uma amostra de disponibilizada pela professora Juliana Mascarenhas, realizar a transformação dos dados de acordo com as diretrizes e criar um relatório

## Procedimentos
 1. Usando o script sql disponibilizado, criei o banco de dados azure_company no MYSQL Workbench e usei o Power BI para regastar os dados
 2. Em seguida, verifiquei os cabeçalhos,para ter uma compreensão inicial de da estrutura dos dados
 3. Modifiquei a coluna `Salary` da tabela `employee` assim o seu formato ficou o mesmo que utilizado no Brasil.
 4. Na tabela `works_on` removi o `essn:88866555` pois de horas trabalhas era 0. Além disso vi a existência de um valor nulo na tabela `employee` do empregado `James Borg`, mas julgando pelos dados é porque ele possui o cargo mais alto entre os empregados.
 5. Separei a coluna `Address` de `employee` e dei o nome de `nAddress, Address,City,State`
 6. Mesclei `employee` e `departament` utilizando o Power BI e criei uma nova tabela com a relação, `employee_departament`
 7. Repeti o processo 6. mas agora com as tabelas do empregado(employee) e gerentes(manager) 
 8. Fiz a mescla das colunas `Fname` e `LName` criando uma unica coluna, `Name`
9.Na tabela `dept_locations` adicionei o nome de cada `departament`
10. Por fim,  criei o relatório utilizado o que já foi visto anteriomente.
