# Atividades de Recuperação - Programação

Este documento apresenta três propostas de atividades práticas de recuperação, focadas em consolidar os conceitos essenciais de cada área da programação.

---

## 📱 1. Programação Mobile
### Atividade: Aplicativo de Lista de Tarefas Favoritas (ToDo List com Persistência Local)

*   **Objetivo:** Avaliar a criação de interfaces mobile, manipulação de estados e armazenamento local de dados.
*   **O que deve ser feito:**
    *   Criar uma tela com um campo de texto e um botão para adicionar tarefas.
    *   Exibir as tarefas em uma lista rolável (ex: `RecyclerView`, `FlatList` ou `ListView`).
    *   Implementar a função de deletar uma tarefa ou marcá-la como concluída ao clicar.
    *   **Desafio de recuperação:** Garantir que as tarefas não sumam quando o aplicativo for fechado (usando *SQLite*, *Room*, *AsyncStorage* ou *Shared Preferences*).

---

## 🎨 2. Programação Front-End
### Atividade: Consumo de API de Filmes ou Clima (Dashboard Dinâmico)

*   **Objetivo:** Avaliar a estruturação de layout responsivo, estilização e consumo de dados assíncronos (APIs).
*   **O que deve ser feito:**
    *   Criar uma página web com uma barra de busca e uma área de exibição de *cards*.
    *   Consumir uma API pública gratuita (como a *PokeAPI*, *OpenWeatherMap* ou *TMDB* Filmes) usando `fetch` ou `axios`.
    *   Exibir os resultados renderizados na tela de forma organizada e responsiva (usando Flexbox ou Grid).
    *   **Desafio de recuperação:** Implementar um mecanismo de tratamento de erros (ex: exibir uma mensagem amigável caso a busca não encontre nenhum resultado ou a API falhe).

---

## ⚙️ 3. Programação Back-End
### Atividade: Desenvolvimento de uma API RESTful para um Sistema de Inventário

*   **Objetivo:** Avaliar a criação de rotas, manipulação de métodos HTTP, validação de dados e integração com banco de dados.
*   **O que deve ser feito:**
    *   Criar um servidor (usando *Node.js/Express*, *Python/FastAPI* ou *Java/Spring Boot*).
    *   Configurar as rotas para gerenciar um produto (Criar, Ler, Atualizar e Deletar - as operações do **CRUD**).
    *   Utilizar os métodos HTTP corretos: `POST` (cadastrar), `GET` (listar), `PUT` (editar) e `DELETE` (remover).
    *   **Desafio de recuperação:** Impedir o cadastro de produtos com valores negativos ou com nomes vazios, retornando o código de status HTTP adequado (ex: `400 Bad Request`).
