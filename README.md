Snippets node-api-cli
======

Snippets node-api-cli é uma [extensão](https://marketplace.visualstudio.com/items?itemName=snippets-node-api-cli.snippets-node-api-cli) do [VS Code](https://code.visualstudio.com/) que são fragmentos de códigos usados na [extensão](https://marketplace.visualstudio.com/items?itemName=snippets-node-api-cli.snippets-node-api-cli) geradora de projetos API em NodeJs [node-api-cli](https://www.npmjs.com/package/node-api-cli).

Após gerar um projeto com o [node-api-cli](https://www.npmjs.com/package/node-api-cli) instale esta [extensão](https://marketplace.visualstudio.com/items?itemName=snippets-node-api-cli.snippets-node-api-cli) de Snippets no seu [VS Code](https://code.visualstudio.com/) que este irá ajudar nas rotinas de manutenção de sua API em Nodejs.

Instalação pela interface
------------
1. Instale o Visual Studio Code, IDE gratuita que pode ser baixada [aqui](https://code.visualstudio.com/);
1. Após abrir o Visual Studio Code, vá em "Extensions" ou use o atalho "Ctrl+Shift+X" (se caso esteja utilizando o sistema operacional Linux ou Windows);
1. Procure por [snippets-node-api-cli](https://marketplace.visualstudio.com/items?itemName=snippets-node-api-cli.snippets-node-api-cli) e clique em "Install";
1. Aguarde a instalação concluír e depois clique em "Reload" para reiniciar o VS Code e assim poderá utilizar o Snippets node-api-cli, conforme mais abaixo.

Instalação por linha de comando
------------
1. Instale o Visual Studio Code, IDE gratuita que pode ser baixada [aqui](https://code.visualstudio.com/);
1. Após abrir o Visual Studio Code, vá no menu "Go" e depois em "Go to file" ou use o atalho "Ctrl+P" (se caso esteja utilizando o sistema operacional Linux ou Windows);
1. No campo que irá abrir digite "ext install snippets-node-api-cli.snippets-node-api-cli" e aperte "Enter".

Snippets para disponíveis
------------

Atualmente estão contemplados somente para documentos Javascript do seu projeto, os com extensão .js. 

Todas os fragmentos de códigos disponíveis começa com "snac-" que é o acrônimo de Snippets node-api-cli.

Segue abaixo todas a opções. 

Snippets para Javascript disponíveis
------------

Digite uma das opções abaixo em um arquivo Javascript (extensão .js) e aperte "Tab" que será gerado o código conforme a descrição. 

- `snac-modelo-padraoMongoose`: Cria um conteúdo padrão para modelo de dados para uso com o [Mongoose](http://mongoosejs.com/).
- `snac-modelo-parametrosPadraoMongoose`: Cria um novos parâmetros padrões do modelo já criado utilizando o [Mongoose](http://mongoosejs.com/), como os campos de registro de usuário que criou e editou o modelo e as datas de criação e edição também.
- `snac-modelo-novoParametroMongoose`: Cria um novo parâmetro no modelo já criado utilizando o [Mongoose](http://mongoosejs.com/).
- `snac-repositorio-padraoMongoose`: Cria um repositório genérico para ser utilizado com modelos criados com o [Mongoose](http://mongoosejs.com/).
- `snac-repositorio-novoComGenericoMongoose`: Cria um repositório com base no repositório genérico padrão do [node-api-cli](https://www.npmjs.com/package/node-api-cli).
- `snac-rota-padrao`: Cria uma rota padrão nos padrões do [node-api-cli](https://www.npmjs.com/package/node-api-cli), que já adicionado os validador de acesso e registro de CRUD utilizados no [node-api-cli](https://www.npmjs.com/package/node-api-cli).
- `snac-configuracao-modelo`: Adiciona no arquivo "config.js" do padrão [node-api-cli](https://www.npmjs.com/package/node-api-cli) uma referência de modelo ao projeto.
- `snac-configuracao-rota`: Adiciona no arquivo "config.js" do padrão [node-api-cli](https://www.npmjs.com/package/node-api-cli) uma referência a rota do projeto.
- `snac-configuracao-modeloERota`: Adiciona no arquivo "config.js" do padrão [node-api-cli](https://www.npmjs.com/package/node-api-cli) um modelo e rota de uma mesma entidade no projeto.
- `snac-controle-padrao`: Cria um controle padrão do [node-api-cli](https://www.npmjs.com/package/node-api-cli), já adicionando uso ao repositório da entidade e ao repositório genérico do padrão do node-cli-api.