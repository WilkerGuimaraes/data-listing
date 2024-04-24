## Home Page

![home_page](https://imgur.com/6jG8u4U.png)

## Criando novos dados

https://github.com/WilkerGuimaraes/data-listing/assets/141461291/6c1a8a9e-3a55-4502-b754-b1a2167fadb1

## Filtrando dados

https://github.com/WilkerGuimaraes/data-listing/assets/141461291/dcd5283b-202c-48f4-a9da-22d7d9f9193a

# Listagem de dados

## 📃 Descrição

Esta é um projeto front-end no qual foi desenvolvido uma página web de listagem de dados. Que oferece um sistema de paginação, criação de um novo dado através de um formulário e filtragem de dados por tags através de uma caixa de diálogo.

## 🛠 Tecnologias

![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

## ⚙ Funcionamento

- O usuário pode criar um novo dado através de um formulário.
- O usuário pode interagir com a lista de dados por meio da paginação presente no projeto.
- O usuário pode filtrar os dados da lista.

Este projeto aborda os conceitos do `react-query` para gerenciar automaticamente o cache de dados no navegador. Ou seja, quando o usuário avança entre as páginas os dados são salvos em cache permitindo assim uma melhor experiência do usuário. Pois quando o usuário retorna para as páginas aos quais ele já tenha carregado anteriormente, os dados daquela página são atualizados instantaneamente.

Para compreender isso, este projeto possui um delay de 2 segundos para que o estado de uma página ao qual o usuário nunca tenha acessado antes seja carregada. Para que quando retornar à página anterior seja possível ver a mudança imediata do estado da lista.

https://github.com/WilkerGuimaraes/data-listing/assets/141461291/ff75112b-baac-4c03-b5eb-0a317235cd37

## 🧰 Recursos

- `json-server`: Este projeto não possui uma API integrada, por isso utiliza o json-server para simular um servidor back-end para fins de teste para armazenar a lista de dados. Os dados ficam salvos no arquivo `server.json`.
- `react-hook-form`: é uma biblioteca React que utiliza React Hooks para gerenciar o estado dos campos de formulários. Neste projeto esta biblioteca esta sendo utilizada para lidar com a validação dos campos e controlar o envio do formulário.
- `zod`: é uma biblioteca de validação de esquemas em TypeScript. Nesta aplicação ela está sendo utilizada para definir o esquema de validação dos dados do formulário.
- `react-query`: é uma biblioteca React que serve para o gerenciamento de estado assíncrono. Seu uso neste projeto é lidar com a mutação de dados quando o formulário é enviado (criação de uma nova tag), serve também para atualizar automaticamente os dados da lista de tags após a mutação ser concluída com sucesso e para gerenciar automaticamente o cache dos dados no navegador.

## 💻 Executando

1. Escolha um diretório na sua máquina, acesse-o pelo terminal e execute o seguinte comando para clonar este repositório:

```

git clone https://github.com/WilkerGuimaraes/data-listing.git

```

2. Acesse este projeto através do seu editor de código e execute o seguinte comando para instalar todas as dependências:

```

npm install

```

3. Após instalar todas as dependências, execute o seguinte comando para executar o json-server:

```

npm run server

```

4. E por fim, execute o seguinte comando para executar o projeto:

```

npm run dev

```

Assim que o projeto estiver rodando, acesse o seu `http://localhost:5173/`

## 🙋‍♂️ Colaboradores

Este projeto foi desenvolvido por mim Wilker Guimarães, em conjunto com a mentoria da Rockeseat com o objetivo de desenvolver e aplicar os meus conhecimentos de desenvolvimento front-end e também aplicar boas práticas utilizando o react para construir interfaces mais funcionais, acessíveis e bonitas.
