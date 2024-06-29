# SPRING DATA JPA - 2024

## JPA

### O que é?

Java Persistense API, é um projeto que faz parte do ecossistema spring para trabalharmos com base de dados nas nossas aplicações Spring de uma forma muito mais fácil.

É também considerado uma especificação para mepeamento objeto relacional em Java. Mapeamento seja de entidades, transformando tudo isso em tabelas e colunas na base de dados.

Faremos isso usando anotações, consultas JPQL e Apis para realizar a interação com a base de dados.

O JPA, portanto, é uma abstração.

Bom, se o JPA é uma abstração, quem irá implementá-lo?

**Entramos na camada de Hibernate!**
<hr>

## Hibernate

### O que é?

Ele irá utilizar por debaixo dos panos do JDBC, para realizar essas transações com a base de dados. Para que seja possível iniciar as conexão, executar querys/transações, etc...
<hr>

## Spring Data JPA

Ele basicamente engloba o JPA. É uma camada de abstração inicial, que inclui os recursos do JPA e também alguns recursos extras (próprios), como implementação do padrão de repositories, criação de consulta na base a partir de nome de atributos (usando métodos findAll, findById, entre outros).

A aplicação Spring irá nos permitir utilizar deste projeto com bancos relacionais (postgres por exemplo) não precisando ficar criando/executando na mão scripts SQL, focando mais nas regras de negócios.
<hr>

## PROJETO

### UML do Projeto
![uml_projeto.png](uml_projeto.png)





## ANOTAÇÕES JPA

