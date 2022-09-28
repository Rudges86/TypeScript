# TypeScript
Estudos de TypeScript
1-Instale o typeScript de forma global
    npm i -g typescript
2- Crie o compilador chmado tsconfig.ts
    tsc --init
3- Basta criar qualquer arquivo com .ts no final
    a.ts
4- Para compilar basta usar no local do arquivo
    tsc a.ts  //tsc nomedoarquivo.ts
    ele irá gerar um arquivo javaScript que sera interpretado pelo nodeJS
5- Pode instalar o ts-node de forma global para que o codeRunner rode os arquivos ts
    npm i -g ts-node
6-Lembre-se sempre de salvar o arquivos

7- Rode o comando npm init -y para gerar o script de configuração
8- Rode o comando npm i -s live-server
9-Dentro do script, crie um com o nome "scripts":{ "start":"live-server"}
10 - Na pasta raiz do projeto, usamos o comando tsc -w, vai ficar compilando o arquivo sempre que ocorra alguma mudança
11-Esse processo é para ficar atualizando todas as mudanças feitas no código para a página
