# Curso de Angular - AlgamoneyUi

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.1.2.

link dos código do curs: https://github.com/algaworks/curso-angular-rest-spring-boot-ui

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Versao do Node, NPM e Angular que foi realizado o curso
```bash
node v8.1.2 & npm 5.0.3
npm install @angular/cli@1.1.2
```

Se preferir você pode instalar o **[NVM](https://github.com/creationix/nvm#installation-and-update)** que possui todas as versões do <u>Node e NPM</u> para instalar:

```bash
# verifique se a versao mais atual do nvm no site:
# https://github.com/creationix/nvm#installation-and-update
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
source ~/.bashrc
nvm --version
nvm ls-remote
nvm install v8.1.2
# instalar versao atual do anuglar
npm install -g @angular/cli

# Instale uma versão anterior, talvez por causa de um bug na versão mais recente. Por exemplo, para obter o 6.0.2:
npm install @angular/cli@6.0.2
npm install -g @angular/cli@1.1.2

# remover o angular/cli shell
sudo npm uninstall -g @angular/cli
```

#### Comando mais utilizados no curso:

```bash
# criando um componente de mensagens inline sem html/css
ng g c message --spec=false --inline-template --inline-style
# criar um projeto
ng new my-first-project
# iniciar o projeto no navegador
ng serve
# inicar em uma porta especifica
ng serve --port 8181
# criando um componente
ng g c bem-vindo --spec=false
ng g c message --spec=false

# Para listar todos modulos NPM instalados faça: 
npm -g ls
# Pare remover todos os modulos NPM instalados faça: 
npm -g rm
# listar os pacotes
npm list
npm -g ls
# remover um pacote instalado
npm uninstall -g @angular/cli
npm uninstall primeng --save
# limpar o cache do npm
npm cache clean

# versao mais atual:
npm install primeng --save

# versao especifica
npm install primeng@4.1.0-rc.2 --save
npm install lodash@4.17.4
# Se você não souber a versão exata do pacote , o NPM permite usar intervalos semânticos para definir a versão. Por exemplo}:
npm install lodash@^4.0.0
npm install primeng@^4.1.0 --save
npm install fontawesome@^4.7.0 --save
npm install font-awesome@^4.7.0 --save

# instalar bootstrap
# link: https://getbootstrap.com/docs/4.1/layout/overview/
npm install bootstrap --save
```

#### Instalando pacotes do curso pelo node:

```bash
# currency no angular:
# https://www.npmjs.com/package/ng2-currency-mask

npm install ng2-currency-mask --save
npm install ng2-currency-mask@4.1.0 --save
npm install -g json-server

# versao especifica
npm install primeng@4.1.0-rc.2 --save
npm install lodash@4.17.4
```



## Referências

- https://www.primefaces.org/primeng-4.3.0/#/setup
- https://www.primefaces.org/primeng-4.3.0/#/tabview
- https://cli.angular.io/
- https://angular.io/cli
- https://github.com/angular/angular-cli/wiki
- https://gist.github.com/d2s/372b5943bce17b964a79
- https://linuxize.com/post/how-to-install-node-js-on-ubuntu-18.04/
- https://www.devpleno.com/json-server-como-criar-uma-rest-api-para-testes-de-forma-simples/
- https://code.tutsplus.com/pt/tutorials/fake-rest-api-up-and-running-using-json-server--cms-27871
- https://github.com/typicode/json-server

**Extensões para o VSCODE:**

- http://www.robsonmoulin.com.br/artigos/front-end/melhores-plugins-para-o-editor-de-codigo-visual-studio-code/

**Diretivas da versao 4:**

* https://v4.angular.io/api/forms/EmailValidator
* https://www.primefaces.org/primeng-4.3.0/#/datatable/selection