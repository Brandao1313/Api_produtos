# API de Produtos

API REST desenvolvida com Spring Boot para consulta de produtos em memória.

## Como executar

Requisitos:

- Java 21
- Maven Wrapper incluído no projeto

Execute:

```bash
./mvnw spring-boot:run
```

No Windows:

```powershell
.\mvnw.cmd spring-boot:run
```

## Endpoints

- `GET /produtos` - lista os produtos disponíveis.
- `GET /produtos/{id}` - consulta um produto pelo ID.
- `GET /produtos/{id}/descricao` - retorna a descrição de consulta do produto.

## Testes

```bash
./mvnw test
```

## Desenvolvimento

Participaram do desenvolvimento deste projeto:

- Anderson Brandao
- Fernanda Vogado
- Daniel Crisostomo