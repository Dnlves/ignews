# **Ignews**

Aplicação desenvolvida durante o bootcamp **IGNITE** da [Rocketseat](https://rocketseat.com.br/) 🚀.

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

  - [Next.js](https://nextjs.org)
  - [TypeScript](https://www.typescriptlang.org/)
  - [Fauna](https://fauna.com)
  - [Stripe](https://stripe.com/br)
  - [Prismic](https://prismic.io/)

## Configurações necessárias para rodar o projeto:

1. Faça um `git clone` desse repositório para um diretório em sua máquina.

2. Acesse o diretório e rode o seguinde comando para
baixar todas as dependências do projeto:
    ```bash
      yarn
    ```
3. Em seguida, crie um aquivo `.env.local` com todas as variaveis ambientes necessárias com base no arquivo `.env.example`.  

4. Para que o projeto funcione também é necessário ter o executável da CLI do Stripe ou a própria CLI do Stripe instalada no seu terminal.

    Como rodar o executável da CLI do Stripe no Linux:
    ```bash
      sudo ./stripe login
      sudo ./stripe listen --forward-to http://localhost:3000/api/webhooks
    ```

5. Finalmente, abra uma nova aba no terminal e rode o comando em modo de desenvolvimento:
    ```bash
      yarn dev
    ```
    O servidor inciará na porta:3000 - acesse <http://localhost:3000>.