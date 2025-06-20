# 🧪 Projetos de Testes Automatizados com Katalon Studio

Este repositório reúne dois projetos de automação de testes desenvolvidos com o **Katalon Studio**, utilizando sites públicos voltados para fins educacionais: [Saucedemo](https://www.saucedemo.com/), e [TodoMVC](https://todomvc.com/).

Os projetos têm como objetivo consolidar conhecimentos em **testes funcionais automatizados**, explorando diferentes fluxos de sistemas reais, como login, cadastro, compras, filtros e interações com a interface.

---

## 🗂 Índice

- [🔸 Projeto Saucedemo](#projeto-saucedemo)
- [🟢 Projeto TodoMVC](#projeto-todomvc)
- [🛠 Ferramentas Utilizadas](#ferramentas-utilizadas)
- [📌 Considerações Finais](#considerações-finais)

---

## 🔸 Projeto Saucedemo

Projeto criado a partir do site [Saucedemo](https://www.saucedemo.com/), uma loja de testes com foco em autenticação, filtros de produtos e processo de compra.

### ✅ Casos de Teste

| Código  | Nome do Caso de Teste                              | Descrição                                                                 |
|---------|----------------------------------------------------|---------------------------------------------------------------------------|
| CT1     | Login com usuário e senha válidos (variáveis)      | Login com dados parametrizados                                            |
| CT2     | Usuário em branco e senha válida                   | Validação de erro ao omitir o usuário                                     |
| CT3     | Usuário e senha em branco                          | Campos vazios no login                                                    |
| CT4     | Usuário válido e senha em branco                   | Erro ao omitir a senha                                                    |
| CT5     | Login com usuário/senha inválidos                  | Tentativa de login com dados incorretos                                   |
| CT6     | Checkout com dados preenchidos                     | Fluxo completo de compra                                                  |
| CT7     | Checkout sem nenhum dado                           | Envio do formulário vazio                                                 |
| CT8     | Checkout sem preencher "Last Name"                 | Campo obrigatório não preenchido                                          |
| CT9     | Checkout sem preencher "Postal Code"               | Campo obrigatório não preenchido                                          |
| CT10    | Checkout com carrinho vazio                        | Validação ao tentar finalizar compra sem produtos                         |
| CT11    | Filtro por nome (Z to A)                           | Verificação da ordenação de produtos                                      |
| CT12    | Logout                                             | Validação do fluxo de logout                                              |
| CT13    | Login com usuário e senha válidos (fluxo direto)   | Login simples sem variáveis                                               |

---

## 🟢 Projeto TodoMVC

O projeto TodoMVC foi utilizado para validar ações básicas de uma lista de tarefas. Os testes simulam interações completas com o CRUD de tarefas.

### ✅ Casos de Teste

| Código | Nome do Caso de Teste                    | Descrição                                                            |
|--------|------------------------------------------|----------------------------------------------------------------------|
| CT1    | Inserir nova tarefa                      | Criação de uma nova tarefa                                           |
| CT2    | Excluir tarefa da lista                  | Remoção de uma tarefa existente                                      |
| CT3    | Limpar tarefas completas                 | Ação de apagar todas as tarefas concluídas                           |
| CT4    | Filtro de Tarefas Ativas                 | Exibição somente das tarefas ativas                                  |
| CT5    | Filtro de Tarefas Completas              | Exibição somente das tarefas finalizadas                             |
| CT6    | Filtro de Todas as Tarefas               | Exibição completa da lista                                           |
| CT7    | Marcar tarefa como concluída             | Interação com o checkbox de finalização                              |
| CT8    | Editar tarefa existente                  | Alteração do conteúdo de uma tarefa                                  |

---

## 🛠 Ferramentas Utilizadas

- **Katalon Studio**  
- **Groovy (linguagem de script)**  
- **Git / GitHub**  
- Testes com **foco na interface gráfica (UI)**  
- Organização por pastas de **Test Cases**, **Object Repository**, e **Test Suites**  

---

## 📌 Considerações Finais

Este repositório representa parte da minha jornada de aprendizagem e transição para a área de **Quality Assurance**. A criação desses projetos me permitiu:

- Consolidar conhecimentos em **automação de testes funcionais**
- Praticar a criação de **cenários realistas**
- Reforçar o uso de boas práticas em **testes com Katalon Studio**
- Desenvolver autonomia em ferramentas amplamente utilizadas no mercado

Caso tenha interesse em conversar sobre QA, compartilhar experiências ou colaborar, fique à vontade para entrar em contato!

---

📧 **Rebeca Visconti**  
💼 [LinkedIn](https://www.linkedin.com/in/rebecavisconti)  
📍 Porto, Portugal
