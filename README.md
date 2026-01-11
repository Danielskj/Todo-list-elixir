📝 Descrição do Projeto
Este projeto é uma Lista de Tarefas (Todo List) desenvolvida com Elixir, utilizando Phoenix Framework e LiveView para a interface dinâmica.
O projeto integra persistência de dados com Ecto e SQLite, e utiliza TailwindCSS junto com daisyUI para estilização.

Funcionalidades principais:

Adicionar novas tarefas.
Marcar tarefas como concluídas.
Deletar tarefas.
Interface interativa sem reload de página (via LiveView).

📌 Informações do Aluno
Nome do Aluno: Carlos Daniel dos Santos Silva
Professor: Sergio Costa
Curso: Engenharia da Computação
Universidade: Universidade Federal do Maranhão (UFMA)

🔗 Link do Tutorial
[Tutorial Original no Notion] https://profsergiocosta.notion.site/Como-Criar-um-App-Todo-List-com-Elixir-e-LiveView-do-Zero-2a8cce97509380eba53fc82bbeb08435

⚙️ Tecnologias Utilizadas
Elixir 1.15+
Phoenix 1.8+
LiveView
Ecto + SQLite
TailwindCSS + daisyUI

Para rodar o projeto:

git clone <URL_DO_REPOSITORIO>
cd elixir_todo_list
Instale as dependências:

mix deps.get


Prepare o banco de dados:

mix ecto.create
mix ecto.migrate


Instale dependências de assets:

mix assets.setup
mix assets.build


Inicie o servidor Phoenix:

mix phx.server

