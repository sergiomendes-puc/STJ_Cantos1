# CANTOS TERESIANOS
## _Companhia de Santa Teresa de Jesus_

[![N|Solid](https://stateresa.com.br/wp-content/themes/mantenedora/assets/img/logo-mantenedora-colorido.png)](https://stateresa.com.br/)



## 1 Hino dos Amigos de Jesus
Olá Jesus, és meu amigo,
Me queres muito e também te quero eu. 
Sei que estarás sempre comigo, 
sei que te levo aqui em meu coração.

**Amigos Tu e eu, oh que felicidade,**   
**amigos para sempre, amigos de verdade.**  

Olá Jesus, vais ajudar-me 
quando te chamo correndo Tu virás. 
Se eu cair vens levantar-me, 
se eu estou contente Tu vens para brincar.

## 2 Girassol
Um girassol florido no jardim,  
buscando a luz do sol, sorriu para mim.  
Eu também sou pequeno girassol,  
buscando luz de Deus: Sou feliz assim!  

**1. Tenho mil sementes de amor prá te dar! (Bis)**

**2. Tenho mil sementes de ternura prá te dar! (Bis)**
**3. Tenho mil sementes de carinho prá te dar! (Bis)**

## 3 Passarinhos
Se os passarinhos voam, eu também quero voar (bis)  
O biquinho para o chão, as asinhas para o ar (bis)  

**O pé, o pé, o pé, a mão, a mão, a mão (bis)**  
**Dê uma volta meu amigo**  
**Aperte a mão do seu irmão (bis)**  

Se os passarinhos pulam....
Se os passarinhos andam...
Se os passarinhos amam...
Se os passarinhos rezam...


## 4 Vem, vem, Espírito Santo

Vem, vem, vem, Espírito Santo. Transforma minha vida, quero renascer.  
Vem, vem, vem, Espírito Santo. Transforma minha vida, quero renascer.  
Quero abandonar-me em seu amor. Encharcar-me em seus rios, Senhor.  
Derrubar as barreiras em meu coração.  
Quero abandonar-me em seu amor. Encharcar-me em seus rios, Senhor.  
Derrubar as barreiras em meu coração.

## 5 Glória
Gló-ó-ria! Gló-ó-ria!  
Ao Pai Criador, Ao Filho Redentor e ao Espírito Glória!  
Ao Pai Criador, Ao Filho Redentor e ao Espírito Glória!  

Ao Pai Criador do mundo, ao Filho Redentor dos Homens,  
Ao Espírito de Amor demos sempre Gló-ó-ria!  
Ao Espírito de Amor demos sempre Gló-ó-ria

## 6 O Senhor é Rei
1. O Senhor é Rei, o Senhor é meu Pastor e Rei  
O Senhor está no céu, / o Senhor está no mar, / na extensão do infinito  
/: Está no céu, está no mar, na extensão do infinito :/  

2. Quando eu vacilar, eu não temerei, pois o Senhor está comigo /  
O Senhor está no céu, / o Senhor está no mar, / na extensão do infinito  
/: Está no céu, está no mar, na extensão do infinito :/

## Antes da morte 
1. Antes da morte e ressurreição de Jesus,/ Ele, na Ceia, quis Se entregar:
Deu-se em comida e bebida pra nos salvar.
  
**E quando amanhecer/ o dia eterno, a plena visão,**  
**Ressurgiremos por crer/ nesta vida escondida no Pão. (bis)**  
  

2. Para lembrarmos a morte, a cruz do Senhor,/ nós repetimos, como Ele fez:
gestos, palavras, até que volte outra vez.
  
3. Este banquete alimenta o amor aos irmãos,/e nos prepara a glória do céu;
Ele é a força na caminhada pra Deus.
  
4. Eis o Pão vivo mandado a nós por Deus Pai!/ Quem o recebe, não morrerá; 
no último dia vai ressurgir, viverá.
  
5. Cristo está vivo, ressuscitou para nós!/ Esta verdade vai anunciar
a toda terra, com alegria, a cantar.



## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
