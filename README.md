# Digital Innovation One: Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot.

------

Acompanhando a aula do professor Rodrigo Peleias foi desenvolvido um pequeno sistema para gerenciamento de pessoas de uma empresa através de uma API REST, criada com Spring Boot.

Durante as aulas foram desenvolvidos e abordados os seguintes tópicos:

* Setup inicial de projeto com o Spring Boot Initialzr.
* Criação de modelo de dados para o mapeamento de entidades em bancos de dados.
* Desenvolvimento de operações de gerenciamento de usuários (Cadastro, leitura, atualização e remoção de pessoas de um sistema).
* Relação de cada uma das operações acima com o padrão arquitetural REST, e a explicação dos conceitos envolvidos durante o desenvolvimento do projeto. 
* Desenvolvimento de testes unitários para validação das funcionalidades.
* Implantação do sistema na nuvem através do Heroku.



Para execução do projeto no terminal é necessário ter o maven instalado, mapeado no PATH nas variáveis de ambiente, no SO Windows, digitando o seguinte comando:



`mvn spring-boot:run`



Após executar o comando acima, basta abrir o seguinte endereço no navegador e visualizar a execução do projeto:



`http://localhost:8080/api/v1/people`



São pré-requisitos para a execução do projeto desenvolvido durante as aulas:

Java versão 11 ou versões superiores.

Maven 3.6.3 ou versões superiores.

