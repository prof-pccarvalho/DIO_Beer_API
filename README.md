# DIO_Beer_API
Desenvolvimento de testes unitários para validar uma API REST de gerenciamento estoques de cerveja

DESCRIÇÃO Neste Labs você irá aprender a testar, unitariamente, uma API REST para o gerenciamento de estoques de cerveja. Vamos construir testes unitários para validar o nosso sistema de gerenciamento de estoques de cerveja desenvolvido em Spring Boot, e também apresentar os principais conceitos e vantagens de criar testes unitários com JUnit e Mockito. Além disso, vamos também mostrar como desenvolver funcionalidades da nossa API através da prática do TDD.

Reconfigurar o pom.xml antes de executar o projeto
O pom.xml aqui está diferente do código disponibilizado pelo instrutor
Instrutor Rodrigo Peleias --> https://github.com/rpeleias-v1/beer_api_digital_innovation_one

Digital Innovation: Expert class - Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja. Nesta live coding, vamos aprender a testar, unitariamente, uma API REST para o gerenciamento de estoques de cerveja. Vamos desenvolver testes unitários para validar o nosso sistema de gerenciamento de estoques de cerveja, e também apresentar os principais conceitos e vantagens de criar testes unitários com JUnit e Mockito. Além disso, vamos também mostrar como desenvolver funcionalidades da nossa API através da prática do TDD.

Durante a sessão, serão abordados os seguintes tópicos:

Baixar um projeto através do Git para desenolver nossos testes unitários. Apresentação conceitual sobre testes: a pirâmide dos tipos de testes, e também a importância de cada tipo de teste durante o ciclo de desenvolvimento. Foco nos testes unitários: mostrar o porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software. Principais frameworks para testes unitários em Java: JUnit, Mockito e Hamcrest. Desenvolvimento de testes unitários para validação de funcionalides básicas: criação, listagem, consulta por nome e exclusão de cervejas. TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento do número de cervejas no estoque. Para executar o projeto no terminal, digite o seguinte comando:

mvn spring-boot:run Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

mvn clean test Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

http://localhost:8080/api/v1/beers

Teste de Classe
Para URL acima, fazer um Post no we.postman.co com o seguinte Json:

{ "name":"Colorado Premium ", "brand":"Colorado", "max":"20", "quantity":"10", "type":"LAGER" }

São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

Java 14 ou versões superiores. Maven 3.6.3 ou versões superiores. Intellj IDEA Community Edition ou sua IDE favorita. Controle de versão GIT instalado na sua máquina. Muita vontade de aprender e compartilhar conhecimento :) Abaixo, seguem links bem bacanas, sobre tópicos mencionados durante a aula:

SDKMan! para gerenciamento e instalação do Java e Maven Referência do Intellij IDEA Community, para download Palheta de atalhos de comandos do Intellij Site oficial do Spring Site oficial JUnit 5 Site oficial Mockito Site oficial Hamcrest Referências - testes em geral com o Spring Boot Referência para o padrão arquitetural REST Referência pirâmide de testes - Martin Fowler Neste link (https://drive.google.com/file/d/1KPh19mvyKirorOI-UsEYHKkmZpet3Ks6/view?usp=sharing) , seguem os slides apresentados como o roteiro utilizado para o desenvolvimento do projeto da nossa sessão.

/* Tive q adicionar em settings-->compiler --> ultima opção --> -Djps.track.ap.dependencies=false por conta do erro: java: Internal error in the mapping processor: java.lang.NullPointerException: Cannot invoke "java.net.URL.toExternalForm()" because "resource" is null at org.mapstruct.ap.internal.processor.DefaultVersionInformation.createManifestUrl(DefaultVersionInformation.java:182) */
