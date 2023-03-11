# BACKEND

Projeto base para rápida implementação de diversas utilidades. O backend conta com uma classe de modelo Sample para uma entidade simples, que deve ser implementada de acordo com a necessidade. As classes de Controle (SampleController), Serviço (SampleService) e camada de Persistência (SampleRepository) estão organizadas e também podem ser implementadas de acordo com as regras de negócio.

Backend em spring-boot 2.7.9, MVC, utiliza Java 1.8. Database utiliza MariaDb ou pode implementar h2 para base em memória em casos sem necessidade de persistência.

### Executando em ambiente local

Para executar essa aplicação em modo local, deve-se executar os comandos:
> mvn clean
> mvn install
> mvn spring-boot:run
>

### Possíveis Erros:

Caso tenha problema ao executar o maven, pode ser permissão de pastas onde a IDE intelliJ não está acessando.
Execute os seguintes comandos dentro da pasta raiz do `backend`:

- `sudo chmod -R 777 ./target`
- `sudo chmod -R 777 ./logs`
- `sudo chmod -R 777 ./.m2`

