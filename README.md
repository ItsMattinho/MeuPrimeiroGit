# MeuPrimeiroGit

Projeto desenvolvido para praticar controle de versão com Git e GitHub.

**Aluno:** Matteo Fernandes

## Estrutura do Projeto

- `docs/`: documentação do projeto.
- `src/`: arquivos da aplicação.

## Tecnologias

- HTML
- CSS
- Git
- GitHub

## Funcionalidades

- Página inicial.
- Página de produtos.
- Página de pedidos.
- Página de contato.

## Questionário

### 1. Qual a diferença entre Working Directory, Staging Area e Repository?

**Working Directory:** é a pasta onde os arquivos do projeto são criados e modificados.

**Staging Area:** é a área intermediária onde os arquivos são preparados para o próximo commit usando `git add`.

**Repository:** é o repositório Git que armazena o histórico dos commits do projeto.

### 2. Qual a diferença entre `git commit` e `git push`?

`git commit` registra as alterações no repositório local. Já `git push` envia os commits do repositório local para o repositório remoto no GitHub.

### 3. Posso fazer vários commits antes de executar `git push`?

Sim. É possível realizar vários commits localmente e depois executar `git push` para enviar todos eles ao GitHub.

### 4. Por que é recomendado fazer commits pequenos e descritivos?

Porque commits pequenos e descritivos facilitam a compreensão do histórico, permitem identificar as alterações realizadas e facilitam a correção de problemas.

### 5. O que acontece com os commits locais antes do `git push`?

Eles permanecem armazenados no repositório local. O GitHub ainda não recebe esses commits até que o comando `git push` seja executado.

### 6. Como verificar no GitHub se os commits foram enviados?

É possível acessar o repositório no GitHub e abrir o histórico de commits. Também é possível usar `git log --oneline` no terminal para verificar os commits localmente.
