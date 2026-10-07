# 📋 Multi-Step Form (Formulário de Avaliação)

Formulário de avaliação de produto dividido em etapas. O usuário informa seus dados, dá uma nota de satisfação com um comentário e, antes de enviar, confere um resumo da avaliação.

Desenvolvido com **React**, **TypeScript** e **Vite**.

## ✨ Funcionalidades

- **Formulário em 3 etapas**: *Identificação*, *Avaliação* e *Envio*.
- **Indicador de progresso** no topo, com ícones, que mostra em qual etapa o usuário está.
- **Etapa de identificação** com os campos *Nome* e *E-mail*.
- **Etapa de avaliação** com 4 níveis de satisfação representados por emojis (*Insatisfeito*, *Poderia ser melhor*, *Satisfeito* e *Muito satisfeito*) e um campo de **comentário**.
- **Etapa de envio** com a mensagem "Falta pouco..." e um **resumo da avaliação** (nome, satisfação e comentário) antes de concluir.
- **Navegação entre etapas** com os botões **Voltar** e **Avançar**; na última etapa o botão vira **Enviar**.

## 🎬 Demonstração

https://github.com/user-attachments/assets/bd3ccc68-dbe2-4f70-a1ea-644253941ec1

## 🛠️ Tecnologias

- **[React 19](https://react.dev/)** — construção da interface
- **[TypeScript](https://www.typescriptlang.org/)** — tipagem estática
- **[Vite](https://vite.dev/)** — ambiente de desenvolvimento e build
- **[React Icons](https://react-icons.github.io/react-icons/)** — ícones da interface
- **[ESLint](https://eslint.org/)** — padronização e qualidade do código
- **CSS** — estilização

## 📁 Estrutura do projeto

```
Multi-Step-Form/
├── public/              # Arquivos estáticos
├── src/                 # Código-fonte da aplicação (React + TypeScript)
├── index.html           # Página HTML principal
├── vite.config.ts       # Configuração do Vite
├── eslint.config.js     # Configuração do ESLint
├── tsconfig.json        # Configuração do TypeScript
└── package.json         # Dependências e scripts
```

## 🚀 Como executar

**Pré-requisito:** [Node.js](https://nodejs.org/) (versão LTS recente) e npm.

1. Clone o repositório:

   ```bash
   git clone https://github.com/jotapefp/Multi-Step-Form.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd Multi-Step-Form
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

5. Abra o endereço exibido no terminal (geralmente `http://localhost:5173`).

### Outros scripts

| Comando           | Descrição                                          |
| ----------------- | -------------------------------------------------- |
| `npm run dev`     | Inicia o servidor de desenvolvimento               |
| `npm run build`   | Verifica os tipos e gera a versão de produção      |
| `npm run preview` | Visualiza localmente a versão de produção          |
| `npm run lint`    | Verifica o código com o ESLint                     |

## 🧭 Como usar

1. Na etapa **Identificação**, preencha seu **nome** e **e-mail** e clique em **Avançar**.
2. Na etapa **Avaliação**, escolha o emoji que representa sua satisfação com o produto e escreva um **comentário**.
3. Clique em **Avançar** para ver o **resumo** da sua avaliação.
4. Se quiser corrigir algo, use **Voltar**; se estiver tudo certo, clique em **Enviar**.

## 👤 Autor

**João Paulo Pinheiro Ferraz de Arruda**

- GitHub: [@jotapefp](https://github.com/jotapefp)
- LinkedIn: [joao-paulo-pinheiro-ferraz-de-arruda](https://www.linkedin.com/in/joao-paulo-pinheiro-ferraz-de-arruda)
