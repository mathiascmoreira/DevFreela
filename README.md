# Formação ASP.NET Core

Bootcamp sobre desenvolvimento de API's ASP.NET Core ministrado pelo Microsoft MVP [Luis Felipe](https://www.linkedin.com/in/luisdeol/). 

Ao longo do bootcamp foi desenvolvida a API de um sistema chamado DevFreela. Esse sistema se trata de uma plataforma em que desenvolvedores buscam por projetos de freelancer. O projeto é relativamente simples, porém foram tratados vários conceitos importantes e boas práticas no desenvolvimento de API's com ASP.NET Core.

___
#### Dos conhecimentos aprendidos no bootcamp, podemos destacar:

* #### Fundamentos do ASP.NET Core:
  Foram apresentados os conceitos básicos do ASP.NET core, como a criação e configuração de um novo projeto (tanto via linha de comando quanto pelo Visual Studio), o protocolo HTTP, API's Restful, Controllers e Actions, Swagger, dentre outros conceitos fundamentais.

* #### Arquitetura Limpa:
  Neste tópico foi abordado o conceito de arquitetura limpa que se aplica muito bem em projetos com ASP.NET Core. Neste módulo, a aplicação foi dividida em sub-projetos como o Core, Application e Infrastructure cada um com as suas responsabilidades específicas.

* #### Persistência de dados com Entity Framework e Dapper e o Padrão Repository:
  A persistência dos dados foi feita utilizando principalmente o Entity Framework mas também foi abordado o uso do Dapper em situações onde se necessita de uma maior perfomance
  na leitura. Além disso, foi utilizado o padrão Repository. Nesse padrão, foram criadas interfaces na camada Core e as implementações foram colocadas na camada de                 infrastructure. Uma das vantagens dessa abordagem é a facilidade de se fazer testes unitários uma vez que a aplicação passa a depender de abstrações.

* #### CQRS:
  Também foi abordado o conceito de CQRS (Command Query Responsibility Segregation), a sua importância e em quais situações é aconselhável o seu uso.

* #### Validação com Fluent Validation:
  A validação dos dados de entrada foi feita utilizando a biblioteca FluentValidation. Esta biblioteca se integra muito bem ao ASP.NET Core sendo possível fazer as validações     utilizando o ModelState do próprio ASP.NET.  

* #### Autenticação e Autorização:
  Outros conceitos de extrema importância que foram abordados no curso foram Autenticação e Autorização. Foram abordados conceitos como token JWT, encriptação de senhas,
  processo de criação de um novo usuário, processo de login, roles, configuração da Autenticação e Autorização no ASP.NET Core dentre outros assuntos.

* #### Testes Unitários:
  Aqui foram abordados os conceitos de testes unitários utilizando a biblioteca xUnit. Foram testadas várias partes da aplicação e também foram abordados os conceitos de Moq,
  TDD, Padrões AAA e Given-When-Then.

* #### Deploy para azure:
  No final do bootcamp, foi feito o deploy da aplicação para o Azure. Neste módulo foram abordados conceitos fundamentais de DevOps, a utilização de serviços do Azure como 
  o Azure SQL Database, dentre outros.

* #### Mini curso de microserviços com Rabbit MQ:
  Por fim, como conteúdo adicional, foram abordados os conceitos de microserviços com a utilização do RabbitMQ.


