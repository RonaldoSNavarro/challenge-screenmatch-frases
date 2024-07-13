## 🔖 Sobre

# ScreenMatch Frases

O projeto ScreenMatch Frases é uma aplicação back-end que fornece frases e pôsteres de séries de forma aleatória com base em informações armazenadas no banco de dados. Essa aplicação se conecta a um front-end que exibe essas informações aos usuários.

## Tecnologias Utilizadas

- **Spring Boot**: Para facilitar a configuração e o desenvolvimento da aplicação.
- **JPA/Hibernate**: Para o mapeamento objeto-relacional e operações de banco de dados.
- **PostgreSQL**: Banco de dados para armazenamento das informações das séries e frases.
- **Anotações do Spring**: Como `@RestController`, `@RequestMapping`, `@GetMapping` e `@Service`, para mapear requisições e rotas, e para definir classes de serviço.

## Estrutura do Projeto

O projeto contém os seguintes pacotes e classes:

### Pacote `br.com.alura.screenmatchfrases.config`

- **Classe `CorsConfiguration`**: Configura as políticas de CORS (Cross-Origin Resource Sharing) para permitir que a API seja acessada por diferentes origens.

### Pacote `br.com.alura.screenmatchfrases.controller`

- **Classe `FraseController`**: Responsável por gerenciar as requisições relacionadas às frases. Mapeia as rotas e define os endpoints da API.

### Pacote `br.com.alura.screenmatchfrases.dto`

- **Classe `FraseDTO`**: Define a estrutura dos dados das frases que serão transferidos entre o cliente e o servidor.

### Pacote `br.com.alura.screenmatchfrases.model`

- **Classe `Frase`**: Representa uma frase da série. Contém atributos como o texto da frase e o identificador da série.

### Pacote `br.com.alura.screenmatchfrases.repository`

- **Classe `FraseRepository`**: Interface que estende `JpaRepository` e permite operações CRUD (Create, Read, Update, Delete) na entidade `Frase`.
- **Classe `SerieRepository`**: Interface que estende `JpaRepository` e permite operações CRUD na entidade `Serie`.

### Pacote `br.com.alura.screenmatchfrases.service`

- **Classe `FraseService`**: Contém a lógica de negócios relacionada às frases. Fornece dados ao `FraseController`.
- 
### Classe `ScreenMatchFrasesApplication`

- **Classe `ScreenMatchFrasesApplication`**: Classe principal do Spring Boot que inicia a aplicação.

## Funcionalidades Implementadas

- **API REST**: Implementação de uma API RESTful para fornecer dados ao front-end.
- **Rotas e Endpoints**: Definição de rotas e endpoints para acessar dados de frases e séries.
- **Integração com Banco de Dados**: Uso do PostgreSQL para armazenar e gerenciar dados de séries e frases.

Com essas funcionalidades, o projeto está pronto para fornecer uma experiência dinâmica e envolvente aos usuários através do front-end conectado.

# Desenvolvedor

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/134724019?v=4" width=115><br><sub>Ronaldo Navarro</sub>](https://github.com/ronaldosnavarro)