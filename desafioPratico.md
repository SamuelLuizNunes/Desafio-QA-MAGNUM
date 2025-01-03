# Casos de Teste para Formulário de Cadastro

## Casos Positivos

### CT01: Cadastro com dados válidos
- **Descrição:** Preencher todos os campos com dados válidos.
- **Massa de Teste:**
    - Nome: Fulano de Tal
    - Email: fulano@email.com
    - CPF: 123.456.789-00
    - Senha: Senha123
- **Passos:**
    1. Preencher o campo **Nome** com "Fulano de Tal".
    2. Preencher o campo **Email** com "fulano@email.com".
    3. Preencher o campo **CPF** com "123.456.789-00".
    4. Preencher o campo **Senha** com "Senha123".
    5. Clicar no botão **Cadastrar**.
- **Resultado Esperado:** O usuário é cadastrado com sucesso e redirecionado para a página de boas-vindas.

## Casos Negativos

### CT02: Nome vazio
- **Descrição:** Tentar enviar o formulário sem preencher o campo **Nome**.
- **Massa de Teste:**
    - Nome: (vazio)
    - Email: cicrano@email.com
    - CPF: 987.654.321-00
    - Senha: Senha456
- **Passos:**
    1. Deixar o campo **Nome** vazio.
    2. Preencher os outros campos com dados válidos.
    3. Clicar no botão **Cadastrar**.
- **Resultado Esperado:** O formulário não é enviado e uma mensagem de erro "Nome é obrigatório" é exibida.

### CT03: Email inválido
- **Descrição:** Inserir um email no formato inválido.
- **Massa de Teste:**
    - Nome: Beltrano de Souza
    - Email: beltrano.souza@email
    - CPF: 111.222.333-44
    - Senha: Senha789
- **Passos:**
    1. Preencher o campo **Nome** com "Beltrano de Souza".
    2. Preencher o campo **Email** com "beltrano.souza@email" (email inválido).
    3. Preencher os outros campos com dados válidos.
    4. Clicar no botão **Cadastrar**.
- **Resultado Esperado:** O formulário não é enviado e uma mensagem de erro "Email inválido" é exibida.

### CT04: CPF inválido
- **Descrição:** Inserir um CPF inválido.
- **Massa de Teste:**
    - Nome: Mariana Pereira
    - Email: mariana.pereira@email.com
    - CPF: 123.456.789-99 (CPF inválido)
    - Senha: Senha123
- **Passos:**
    1. Preencher o campo **Nome** com "Mariana Pereira".
    2. Preencher o campo **Email** com "mariana.pereira@email.com".
    3. Preencher o campo **CPF** com "123.456.789-99" (CPF inválido).
    4. Preencher o campo **Senha** com "Senha123".
    5. Clicar no botão **Cadastrar**.
- **Resultado Esperado:** O formulário não é enviado e uma mensagem de erro "CPF inválido" é exibida.

### CT05: Senha fraca
- **Descrição:** Inserir uma senha fraca (menor que 8 caracteres).
- **Massa de Teste:**
    - Nome: José Martins
    - Email: jose.martins@email.com
    - CPF: 987.654.321-00
    - Senha: 12345 (senha com menos de 8 caracteres)
- **Passos:**
    1. Preencher o campo **Nome** com "José Martins".
    2. Preencher o campo **Email** com "jose.martins@email.com".
    3. Preencher o campo **CPF** com "987.654.321-00".
    4. Preencher o campo **Senha** com "12345" (senha com menos de 8 caracteres).
    5. Clicar no botão **Cadastrar**.
- **Resultado Esperado:** O formulário não é enviado e uma mensagem de erro "Senha muito curta" é exibida.

### CT06: Senha e confirmação de senha diferentes
- **Descrição:** Inserir senhas diferentes nos campos de senha e confirmação de senha.
- **Massa de Teste:**
    - Nome: Lucas Almeida
    - Email: lucas.almeida@email.com
    - CPF: 555.666.777-88
    - Senha: Senha123
    - Confirmar Senha: Senha456
- **Passos:**
    1. Preencher o campo **Nome** com "Lucas Almeida".
    2. Preencher o campo **Email** com "lucas.almeida@email.com".
    3. Preencher o campo **CPF** com "555.666.777-88".
    4. Preencher o campo **Senha** com "Senha123".
    5. Preencher o campo **Confirmar Senha** com "Senha456".
    6. Clicar no botão **Cadastrar**.
- **Resultado Esperado:** O formulário não é enviado e uma mensagem de erro "As senhas não coincidem" é exibida.

## Observações
- **Validação de campos obrigatórios:** Certifique-se de que todos os campos obrigatórios estão sendo validados corretamente.
- **Validação de formato:** O formato de email, CPF e senha deve ser validado conforme regras de negócio.
- **Feedback ao usuário:** Mensagens de erro devem ser claras e informativas para que o usuário saiba exatamente o que precisa corrigir.
