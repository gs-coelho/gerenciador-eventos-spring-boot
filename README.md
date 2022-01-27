# spring-boot-LPII

Um pequeno projeto Spring Boot desenvolvido ao longo do 4º Bimestre da disciplina de Linguagem de Programação II, do 3º ano do curso de Informática do CEFET-MG de 2021.

Esse projeto está sendo desenvolvido seguindo o [curso tutorial da Michelli Brito de Spring Boot](https://www.youtube.com/playlist?list=PL8iIphQOyG-DHLpEx1TPItqJamy08fs1D).

O desenvolvimento do projeto se deu ao longo de todo o bimestre, através de questionários em que parte do projeto era realizada.

## Questionário 09/12/21
Foram implementados os vídeos 1, 2 e 3.

Primeiro, foi criado o projeto Spring Boot, utilizando o Spring Initializr.

Em seguida, criei algumas views, controllers e modelos, utilizando algumas anotações do Spring, como @Controller, @RequestMapping e @Entity.

Por fim, criei uma classe DataConfiguration para configurar a conexão com o banco de dados. Nesse caso, utilizei um banco de dados diferente do tutorial: ao invés de adicionar ao pom.xml o conector do MySQL, adicionei o do MariaDB, já que era o banco de dados que já tinha instalado.

## Questionário 16/12/21
Foram implementados os vídeos 4, 5 e 6.

Aqui, criei o EventoRepository, e o utilizei para buscar uma lista de eventos. Também adicionei o Materialize CSS ao projeto, para facilitar a estilização. Apenas uma estilização muito básica foi feita, para testar a biblioteca.

## Questionário 06/01/22
Foram implementados os vídeos 7, 8 e 9.

Nesta aula, utilizei um pouco mais o Materialize CSS para adicionar estilo para as páginas. Criei também uma página para visualizar os detalhes do evento. Por fim, criei uma entidade Convidado, que se relaciona com o Evento. Criei um pequeno formulário para adicionar novos convidados ao banco de dados.

## Questionário 13/01/22
Foram implementados os vídeos 10, 11 e 12.

Nesta aula, usei o ConvidadoRepository para salvar os convidados no banco de dados e buscar uma lista deles para ser exibida. Além disso, usei as anotações de validação para validar os campos dos objetos, exibindo mensagens de aviso através de um th:block do Thymeleaf. Para fazer isso, tive que adicionar a dependencia [spring-boot-starter-validation](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation), necessária para que a integração do framework com os validadores funcione.

## Questionário 20/01/22
Foram implementados os vídeos 13 e 14.

Neste último questionário, melhorei ainda mais a estilização do sistema com o Materialize, além de permitir que os ecentos e convidados sejam removidos.