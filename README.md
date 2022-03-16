# Spring_AWS

Repositório destinado a seguir o curso Crie a infraestrutura de microsserviços Spring Boot em cluster com AWS CDK, usando ECS, SNS, SQS, RDS, DynamoDB e S3 da Udemy Ministrado pelo professor Paulo Siécola.

## Seção 1: Introdução

Aula 01. Conteúdo do curso

Explicou onde e como vamos utilizar as paradas da AWS.

### 2. Conceitos iniciais de AWS

Explicações basicas sobre AWS, basicamente os tipos de conta pago e free, e ainda tem as paradas das regiões, que basicamente para cada região pode ser cobrado de maneira diverente, e em cada região o recurso não é acessado por outra região.

Região é localidade.

Amazon ECS - Elastic Container Service

Fargate

Application Load Balancer

Virtual Private Cloud

Relational Database Service

DynamoDb

Simple Notification Service

Simple Queue Service

Simple Storage Service

CloudWatch

### 3. Preparação do ambiente

Só seguir o PDF que o mano mandou.

## Seção 2: Conceitos de Spring Boot

### 4. Criando o primeiro projeto

Aqui é o basico mesmo de criar projeto spring, mais ele deixou ainda explicou.

### 5. Projeto base com versão definida do Java e do Spring Boot

Aqui ele deixa dois projetos prontos para download caso tu seja uma mula e não consiga criar o projeto solo.

### 6. Abrindo o projeto no IntelliJ IDEA

Aqui ele mostra como abrir o seu projeto no intellij.

### 7. Criando o primeiro endpoint REST

Aqui ele mostra como fazer uma endpoint utilizando o Spring com Gradle, parece ser interessante essa parada do gradle ai mais tem que ser mais estudado, detalha interessante é o tal do actuator que o proprio spring disponibiliza, que basicamente ele deixa um endpoint de pé tipo em prod para você poder consultar se ta tudo de pé.

### Teste 1: Anotações para criar um controller e um endpoint

Aqui exercicios bem basicos e simples.

### Teste 2: Parâmetros e retornos de uma operação

Aqui também.

## Seção 3: Executando a aplicação em um container Docker

### 8. Visão geral do Docker

Aqui ele só explicou como vai funcionar as paradas.

### 9. Criando o repositório no Docker Hub

Só criamos uma repositório no dockerhub e mais nada.

### 10. Preparando o projeto para gerar a imagem do Docker

Criamos uma imagem docker com o java 15 e umas paradas do Gradle, to começando a achar complicado de mais para nada.

### 11. Executando a aplicação em um container Docker no IntelliJ IDEA

Aqui simplemente conectamos no dockerhub e criamos um container apartir da imagem que criamos e exposmos a porta 8080, so isso.

## Seção 4: Introdução ao AWS CloudFormation

### 12. Introdução ao AWS CloudFormation

Aqui ele explica o conceito de stack, que seriam os passos a serem executados na AWS quando você vai subir alguma coisa, seja validação ou preparação de ambiente, como cloud formation.

### 13. Analisando stacks, eventos, recursos e parâmetros

Aqui ele mostrou uma stack que ele criou, basicamente uma stack é um conjunto de passos que a AWS executa para poder subir todo um ambiente com todos os recursos necessarios para a sua aplicação rodar,
nesse caso pode ser recurso de rede, habilitar ou desabilitar portas, fazer redirecionamento, subir banco de dados etc.

nessa aula ele mostrou uma dele que não tinha nada de mais.

### Teste 3: Stacks

Teste mequetrefe.

### 14. Apagando uma stack

Aqui quando você apaga uma stack ela apaga tudos os recursos que ela possui, o que pode dar merda se você colocar todos os seus recursos numa mesma stack.

### Teste 4: Excluindo uma stack

Mais uma Teste mequetrefe.

## Seção 6: Introdução ao AWS ECS com Fargate

### 20. Arquitetura com AWS ECS e Fargate

Aula Introdutória.

### 21. VPC - Virtual Private Cloud

VPC - Virtual Cloud Private - é uma rede privada que só funciona dentro da AWS e que só pode ser acessivel de dentro e por dentro da AWS.

### 22. Cluster

O Cluster é onde você coloca tudo , o AWS EC2 é basicamente onde criamos as instancias dos recursos que precisamos, e o AWS Fargate é o gerenciador de containers.

basicamente o fargate não cria uma nova instancia dentro do container ecs ele utiliza o que já ta la, e ainda como ele é um gerenciador pelo que eu vi ele não fica subindo novas instancias de nada.

### Teste 6: AWS ECS com Fargate

Mais uma Teste mequetrefe.
