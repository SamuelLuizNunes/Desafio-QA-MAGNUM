# Parte 1: Teste Teórico

## 1. Diferença entre testes funcionais e testes de regressão
Testes funcionais verificam se o sistema realiza corretamente as funcionalidades de acordo com os requisitos.

Testes de regressão garantem que alterações ou correções no sistema não causaram problemas em funcionalidades que já estavam funcionando.

---

## 2. Diferença entre um teste funcional e um teste não funcional
Teste funcional verifica se o sistema faz o que ele foi projetado para fazer, ou seja, se ele cumpre as funcionalidades corretamente.

Teste não funcional foca em aspectos como desempenho, usabilidade e segurança, ou seja, verifica como o sistema se comporta sob diferentes condições.

---

## 3. Teste de caixa branca e teste de caixa preta
Caixa branca: Testa o funcionamento interno do sistema, olhando o código.

Caixa preta: Testa o sistema sem ver o código, focando nas entradas e saídas.

---

## 4. O que é BDD e como ele se relaciona com o processo de QA?
BDD (Behavior Driven Development) é uma técnica de desenvolvimento que utiliza uma linguagem simples e legível para descrever o comportamento esperado do sistema. Os testes são escritos em formato de cenários, como "Dado que", "Quando" e "Então", que descrevem a interação do usuário com o sistema.

No processo de QA, o BDD facilita a colaboração entre desenvolvedores e testadores, ajudando a criar testes automatizados mais próximos dos requisitos de negócio e garantindo que todos estejam alinhados quanto às expectativas do sistema.

---

## 5. Qual a importância do QA na equipe técnica?
O QA é importante porque garante que o produto funcione corretamente, sem falhas, e atenda às expectativas do usuário. Ele ajuda a detectar problemas cedo, evitando surpresas no final e garantindo um produto mais confiável e de melhor qualidade.

---

## 6. Qual linguagem e qual framework você já utilizou para automação de testes?
Eu já utilizei Java, Rest Assured, JUnit e Selenium WebDriver para automação de testes. O Rest Assured foi utilizado para testes de API, o Selenium WebDriver para testes de interface web, e o JUnit para estruturar e organizar os testes em Java.

---

## 7. Como você reportaria um bug capturado durante um teste manual?
Eu reportaria um bug capturado durante um teste manual da seguinte forma:

1. **Título claro e objetivo**: Descrição breve do problema.
2. **Descrição detalhada**: Explicação completa do que aconteceu, como reproduzir o erro e o comportamento esperado.
3. **Passos para reproduzir**: Lista de ações que levam ao erro.
4. **Resultado esperado**: O que deveria ter acontecido.
5. **Resultado atual**: O que realmente aconteceu.
6. **Captura de tela ou vídeo**: Se possível, para ilustrar o erro.
7. **Informações adicionais**: Ambiente, versão do sistema, logs de erro, entre outros dados relevantes.

### Exemplo:

- **Título**: Erro ao tentar submeter o formulário de cadastro.
- **Descrição**: Ao preencher os campos de nome e email e tentar enviar o formulário, a página retorna um erro inesperado.
- **Passos**:
    1. Acessar a página de cadastro.
    2. Preencher os campos de nome e email.
    3. Clicar no botão "Enviar".
- **Resultado esperado**: O formulário é enviado com sucesso.
- **Resultado atual**: A página exibe um erro "Campo obrigatório não preenchido".
- **Anexo**: Screenshot mostrando o erro.

---

## 8. Como era um dia na sua rotina de QA na sua última experiência?
Minha rotina diária incluí:

1. **Participação na daily**: Alinhamento com a equipe sobre o progresso dos testes e possíveis impedimentos.
2. **Gestão dos testes no Octane**: Acompanhamento dos testes e dos status no Octane, garantindo que tudo estivesse documentado corretamente.
3. **Execução de testes manuais**: Realização de testes de funcionalidades e regressão.
4. **Interação com desenvolvedores**: Discussões para esclarecer problemas encontrados e entender novas funcionalidades.
5. **Manutenção e criação de novos cenários na automação**: Atualização e expansão dos testes automatizados.
6. **Reteste**: Execução de testes em correções de bugs para garantir que os problemas foram resolvidos.

O foco é garantir qualidade e eficiência no processo de testes.
