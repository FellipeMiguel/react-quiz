# React Quiz App

Este é um projeto de um aplicativo de quiz desenvolvido com React.

## Funcionalidades

- Criação de quizzes personalizados.
- Interface amigável e responsiva.
- Feedback imediato para respostas corretas ou incorretas.
- Suporte para múltiplas categorias e níveis de dificuldade.

## Pré-requisitos

- Node.js instalado.
- Gerenciador de pacotes npm ou yarn.

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/FellipeMiguel/react-quiz.git
```

2. Navegue até o diretório do projeto:

```bash
cd react-quiz
```

3. Instale as dependências:

```bash
npm install
```

## Uso

1. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

2. Abra o navegador e acesse `http://localhost:5173`.

## Estrutura de Dados

Os dados das perguntas estão armazenados no arquivo `src/data/questions.json` no seguinte formato:

```json
[
  {
    "question": "Qual é a capital da França?",
    "options": ["Paris", "Londres", "Berlim", "Madri"],
    "answer": "Paris"
  },
  {
    "question": "Qual é o maior planeta do sistema solar?",
    "options": ["Terra", "Júpiter", "Marte", "Saturno"],
    "answer": "Júpiter"
  }
]
```

## Scripts Disponíveis

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Cria uma versão otimizada para produção.
