# Bootcamp Database Experience da DIO

## "Este é o primeiro bootcamp sobre Banco de Dados da DIO para profissionais que procuram uma experiência rápida em Ciência de Dados para se aprimorar nos principais conceitos de banco de dados SQL e NoSQL. No Database Experience você vai passar por 54 horas de imersão, com experiências educacionais e mentorias exclusivas sobre modelagem de dados, SGBD, EER, arquitetura, queries entre outras. Após gerar o seu certificado de conclusão, o seu perfil ficará disponível para as empresas parceiras da DIO que estão contratando."

## Entrega do primeiro desafio "Refinando um projeto conceitual de Banco de Dados - E-commerce"

### Objetivo

### Refine o modelo apresentado acrescentando os seguintes pontos abaixo

1. Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;

2. Pagamento – Pode ter cadastrado mais de uma forma de pagamento;

3. Entrega – Possui status e código de rastreio.

### Coloquei o tipo na mesma entidade "cliente" e a regra de negócio deverá ser feita pelo Front End, ao escolher o tipo ele vai preencher as colunas corretas

### Criei uma nova entidade para cadastrar os tipos de pagamento e uma nova para o rastreamento das entregas

### segundo objetivo: criar um novo modelo de ordem de serviço para uma oficina mecânica

### Narrativa

1. Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
2. Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas
3. Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
4. A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
5. O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
6. A mesma equipe avalia e executa os serviços
7. Os mecânicos possuem código, nome, endereço e especialidade
8. Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
