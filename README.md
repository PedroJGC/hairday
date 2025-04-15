# Hair Day

## 📝 Descrição

Hair Day é uma aplicação web para gerenciamento de agendamentos de corte de cabelo. A plataforma permite que profissionais de salões de beleza organizem seus horários de atendimento de forma eficiente, oferecendo um sistema intuitivo para criação, visualização e cancelamento de agendamentos.

## 🚀 Funcionalidades

- **Agendamento de Horários**: Permite criar novos agendamentos com nome do cliente, data e horário.
- **Visualização por Período**: Organiza os agendamentos em períodos do dia (manhã, tarde e noite).
- **Cancelamento de Reservas**: Possibilidade de cancelar agendamentos já realizados.
- **Interface Responsiva**: Design adaptado para diferentes tamanhos de tela.

## 🛠️ Tecnologias Utilizadas

- **Vanilla JavaScript**: Desenvolvimento frontend sem frameworks.
- **HTML5 & CSS3**: Estruturação e estilização da interface.
- **Módulos ES6**: Organização do código em módulos JavaScript.
- **Webpack**: Bundling e build do projeto.
- **JSON Server**: Backend simulado para armazenamento de dados.
- **Day.js**: Biblioteca para manipulação de datas.
- **Babel**: Transpilação de JavaScript moderno.
- **ESLint & Prettier**: Padronização e formatação de código.

## 🔧 Instalação

1. Clone o repositório:

```bash
git clone [URL_DO_REPOSITÓRIO]
cd hairday
```

2. Instale as dependências:

```bash
npm install
```

3. Execute o servidor de desenvolvimento:

```bash
npm run dev
```

4. Em outro terminal, execute o servidor de API:

```bash
npm run server
```

## 📚 Estrutura do Projeto

```
hairday/
├── src/
│   ├── assets/       # Imagens e recursos estáticos
│   ├── libs/         # Bibliotecas externas
│   ├── modules/      # Módulos da aplicação
│   │   ├── form/     # Lógica do formulário de agendamento
│   │   └── schedules/# Lógica de visualização e gerenciamento
│   ├── services/     # Serviços de API
│   ├── styles/       # Arquivos CSS
│   └── utils/        # Funções utilitárias
├── index.html        # Página principal
├── server.json       # Banco de dados JSON
└── webpack.config.js # Configuração do Webpack
```

## 💻 Como Usar

1. Acesse a aplicação no navegador (geralmente em http://localhost:8080).
2. Selecione uma data no calendário.
3. Escolha um horário disponível dentre os períodos (manhã, tarde ou noite).
4. Insira o nome do cliente.
5. Clique em "Agendar" para confirmar.
6. Visualize os agendamentos do dia na seção lateral.
7. Para cancelar um agendamento, clique no ícone de cancelamento ao lado do nome.

## 👨‍💻 Autor

- Pedro Carvalho

## 📄 Licença

Este projeto está sob a licença [inserir licença aqui].
