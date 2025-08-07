# api_med

Api de consultas médicas desenvolvida em Java utilizando o framework Spring na versão 3. Este projeto foi criado como parte do curso oferecido pela Alura.

## Funcionalidades

- Cadastro de médicos com informações pessoais, endereço e especialidade.
- Atualização de dados médicos.
- Listagem de médicos ativos com paginação.
- Exclusão lógica de médicos.

## Estrutura do Projeto

O projeto segue a estrutura MVC (Model-View-Controller):

- **Model**: Contém as entidades `Medico` e `Endereco`, responsáveis por mapear as tabelas do banco de dados.
- **Controller**: A classe `MedicoController` gerencia as requisições relacionadas aos médicos.
- **Repository**: A interface `MedicoRepository` permite interagir com o banco de dados.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **Spring Boot 3**: Framework para desenvolvimento de aplicações Java.
- **Jakarta Validation**: Para validação dos dados recebidos.
- **JPA (Java Persistence API)**: Para mapeamento objeto-relacional e manipulação do banco de dados.

## Como Executar

1. Certifique-se de ter o Java 17 ou superior instalado.
2. Clone o repositório:
   ```bash
   git clone https://github.com/viniruggeri/api_med.git
   ```
3. Navegue até o diretório do projeto:
   ```bash
   cd api_med
   ```
4. Execute o projeto:
   ```bash
   ./mvnw spring-boot:run
   ```

## Licença

Este projeto está licenciado sob a Licença Apache 2.0. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
