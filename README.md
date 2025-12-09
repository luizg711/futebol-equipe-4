# ⚽ Projeto MongoDB - Futebol Brasileiro

Projeto da disciplina de Gerenciamento de Dados (GDI) - 2023.1.
O objetivo é modelar um banco de dados NoSQL para gerenciar campeonatos, times e jogadores.

## 👥 Equipe
* Luiz Felipe
* Pedro Henrique
* Guilherme Muniz
* Fábio Henrique
* Júlia Andrade
* Sofia Remides
* João Lucas

## 🛠 Tecnologias
* **MongoDB Atlas** (Banco na Nuvem)
* **VS Code** (Playground para scripts)

## 📂 Estrutura do Projeto
A organização dos arquivos foi dividida para separar a carga de dados das consultas:

```text
/
├── .gitignore               # Arquivos ignorados pelo Git
├── README.md                # Documentação do projeto
├── datasets/                # Dados brutos em JSON (para referência ou importação externa)
│   ├── times.json
│   ├── jogadores.json
│   └── campeonatos.json
└── projeto_futebol/         # Pasta principal dos scripts (Execução no VS Code)
    ├── setup.mongodb        # 1. Script de limpeza e carga inicial (Seed)
    └── queries.mongodb      # 2. Script de consultas, agregações e testes


```
## 📋 Checklist Implementado
O projeto cobre 31 itens obrigatórios, incluindo:
- [x] CRUD Completo (Insert, Update, Delete, Find)
- [x] Agregações Complexas ($lookup, $group, $sum)
- [x] Índices de Texto ($text, $search)
- [x] Scripts Legados (MapReduce)

## 🚀 Como rodar
1. Instale a extensão "MongoDB for VS Code".
2. Configure sua Connection String.
3. Abra a pasta projeto_futebol no seu VS Code.
4. Execute primeiro o arquivo setup.mongodb (clique no botão "Play" no canto superior direito) para criar e popular o banco.
5. Em seguida, execute o arquivo queries.mongodb para rodar as consultas e validações do checklist.


## Nota: 
A pasta datasets/ contém os mesmos dados inseridos pelo script de setup, disponibilizados separadamente caso seja necessário utilizar ferramentas de importação como o mongoimport.
