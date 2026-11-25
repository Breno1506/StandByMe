# ProjetoIndividual-3

# Stand By Me

### Qual personagem de JoJo você é?

Website com o tema do anime **JoJo's Bizarre Adventure**. O usuário se cadastra, faz login, responde ao quiz, vota no personagem favorito, avalia o site e acompanha os resultados em um dashboard com gráficos.

O objetivo é guardar as respostas dos fãs em um banco de dados e mostrá-las de forma visual, sem planilhas e sem contagem manual.

Projeto individual da SPTech, turma 1ADSB.

## Funcionalidades

- **Cadastro e login** com nome, email, senha e confirmação de senha
- **Quiz de personalidade** que define qual personagem de JoJo combina com você
- **Personagem favorito**, com votos que alimentam o dashboard
- **Avaliação do site**
- **Dashboard** com gráficos dos personagens mais escolhidos, usuários cadastrados e resultados do quiz

## Tecnologias

| Camada | Tecnologias |
| --- | --- |
| Front-end | HTML, CSS, JavaScript e Chart.js |
| Back-end | Node.js |
| Banco de dados | MySQL |
| Ferramentas | Git, GitHub e Visual Studio Code |

## Estrutura do projeto

```
├── app.js                  # Sobe o servidor e registra as rotas
├── .env                    # Credenciais e porta (fora do GitHub)
├── database/
│   └── script.sql          # Criação do banco e das tabelas
├── public/                 # Telas, CSS, JavaScript do front e imagens
└── src/
    ├── database/config.js  # Conexão com o MySQL
    ├── routes/             # Endereços da API
    ├── controllers/        # Validação dos dados
    └── models/             # Comandos SQL
```

O caminho de uma requisição é: front-end (fetch) → rota → controller → model → banco de dados. A resposta volta pelo mesmo caminho.

## Como rodar

1. Instale as dependências:

```bash
npm install
```

2. Execute o arquivo `database/script.sql` no MySQL Workbench ou no terminal do MySQL para criar o banco e as tabelas.

3. Crie o arquivo `.env` na raiz do projeto com as credenciais do banco e a porta do servidor.

4. Inicie o servidor:

```bash
npm start
```

5. Acesse no navegador: http://localhost:8080

## ODS

O projeto se relaciona com o **ODS 5, Igualdade de Gênero**, da ONU, por meio da representatividade de **Jolyne Cujoh**, protagonista de *Stone Ocean* e a única protagonista mulher entre as partes principais da obra.
