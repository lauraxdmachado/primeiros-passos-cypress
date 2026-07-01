# Primeiros Passos com Cypress

## Sobre o projeto
Este projeto foi desenvolvido durante meus estudos de automação de testes utilizando Cypress.
O objetivo foi aprender os conceitos báasicos de testes End-to-End (E2E), compreender a estrutura da ferramenta e praticar a automação de cenários de login emuma aplicação web.
Os testes foram realizados no ambiente de demonstração do OrangeHRM, amplamente utilizado para estudos e prática de testes de software.

## Tecnologias Utilizadas
- Cypress
- JavaScript
- Node.js
- Git Bash
- GitHub
- VS Code

___

## Cenários Automatizados
### Login com Sucess

#### Objetivo: 
Validar o acesso ao sistema utilizando credencias válidas.

#### Passos:
1. Acessar a página de login.
2. Informar usuário válido.
3. Informar senha válida.
4. Clicar no botão de login.

#### Resultado Esperado:
O usuário deve acessar o sistema com sucesso.

___

### Login com Fail

#### Objetivo: 
Validar o comportamento do sistema ao receber credenciais inválidas.

#### Passos:
1. Acessar a página de login.
2. Informar usuário inválido ou senha incorreta.
3. Clicar no botão de login.

#### Resultado Esperado:
O sistema deve impedir o acesso do usuário.

____

## Aprendizados
Durante o projeto pratiquei:
* Estruturção de testes automatizados E2E;
* Utilização de seletores para localizar elementos da interface;
* Interação com campos de formulário e botões;
* Organização de testes utilizando Cypress;
* Versionamento de código com Git e GitHub.

___

## Estrutura do Projeto

cypress/<br>
├── e2e/<br>
│   ├── login.spec.cy.js<br>
│   └── newFile.js<br>
├── fixtures/<br>
|   ├── userdata.json<br>
├── support/<br>
|   ├── commands.js<br>
|   └── e2e.js<br>
cypress.config.js<br>
package-lock.json<br>
package.json<br>
README.md<br>


