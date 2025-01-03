# Tipos de Requisições em uma API

As APIs utilizam métodos HTTP para realizar operações. Os métodos mais simples e usados são:

## 1. **GET**
Usado para **obter dados** de um servidor. Quando você faz uma requisição GET, está pedindo para visualizar um recurso ou dados.

### Exemplo:
- **GET /usuarios**
- **Descrição:** Retorna uma lista de usuários.

## 2. **POST**
Usado para **enviar dados** ao servidor, geralmente para criar um novo recurso.

### Exemplo:
- **POST /usuarios**
- **Descrição:** Cria um novo usuário, enviando as informações no corpo da requisição.

## 3. **PUT**
Usado para **atualizar completamente** um recurso existente. Substitui todos os dados do recurso.

### Exemplo:
- **PUT /usuarios/123**
- **Descrição:** Atualiza todos os dados do usuário com ID 123.

## 4. **PATCH**
Semelhante ao PUT, mas usado para **atualizações parciais** de um recurso. Apenas os dados fornecidos são alterados.

### Exemplo:
- **PATCH /usuarios/123**
- **Descrição:** Atualiza parte dos dados do usuário com ID 123 (por exemplo, apenas o e-mail).

## 5. **DELETE**
Usado para **remover** um recurso do servidor.

### Exemplo:
- **DELETE /usuarios/123**
- **Descrição:** Exclui o usuário com ID 123.

---


## Tipos de Autorização de Acesso

- **Bearer Token (OAuth)**: Utiliza um token de autenticação que é enviado nas requisições para acessar recursos protegidos.
- **API Key**: Uma chave de acesso única que é usada para autenticar a requisição.
