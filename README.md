# Cafeteria

Projeto criado para a matéria de Programação visual e autoria web. 
Consiste em um e-commerce para uma cafeteria imaginária que eu apelidei de "Tech Bistro". A página foi desenvolvida em HTML, CSS(bootstrap) e JavaScript puro, utilizando uma API local criada com json-server para fornecer os dados dos produtos.


# Como rodar o projeto

1. Instalar o Node.js

Se ainda não tiver o Node instalado, baixe em:

➡ https://nodejs.org/

Após a instalação, abra o PowerShell ou Terminal e verifique:

node -v
npm -v


Se aparecer versões, está tudo certo.

2. Abrir o projeto no terminal

No Windows, clique com o botão direito dentro da pasta do projeto e selecione:

"Abrir no Terminal"
ou
"Abrir no PowerShell"

Ou navegue manualmente:

cd caminho/da/sua/pasta

3. Instalar as dependências

Dentro da pasta do projeto, execute:

npm install


Isso irá instalar o json-server automaticamente, pois ele já está listado no package.json.

4. Iniciar a API local

Execute:

npx json-server db.json


Ou, se preferir, usando o script:

npm run server


A API será iniciada em:

http://localhost:3000/coffee


IMPORTANTE: deixe essa janela do terminal aberta enquanto usa a aplicação.

5. Abrir o site

Basta abrir o arquivo:

index.html


Pode ser dando dois cliques ou arrastando para o navegador.

O site já começa funcionando com:

Produtos carregados da API

Carrinho dinâmico

Finalização da compra

## 📁 Estrutura do Projeto

```bash
/
├── index.html       # todo o site em uma página só
├── db.json          # banco de dados da API local
├── package.json     # configuração do projeto Node
├── package-lock.json
└── node_modules/    # criado automaticamente pelo npm

