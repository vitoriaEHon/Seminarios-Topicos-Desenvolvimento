
#   Tecnologias de Desenvolvimento Frontend
##   Angular (https://angular.io/) 

## Introdução
O que é o Angular? O Angular é um framework de código-fonte aberto e front-end baseado em TypeScript desenvolvido pelo Google com objetivo de aprimorar o processo de criação de aplicativos web.  O Angular é o upgrade do AngularJS. Qual problema o desenvolvedor pode enfrentar na criação de um app web? Quando as pessoas criam aplicativos para a internet que são bem complicados, elas têm que enfrentar muitos problemas. Coisas como guardar informações importantes, fazer com que os botões e coisas na tela funcionem direitinho, fazer o site mudar de página sem carregar tudo de novo e fazer com que coisas aconteçam na hora certa, mesmo que aconteçam ao mesmo tempo. Como o Angular busca amenizar este problema? O Angular é uma ferramenta que permite dividir o aplicativo em pedacinhos, com uma arquitetura baseada em componentes, que são fáceis de entender e usar de novo em outras partes. Ele permite que o usuário use HTML estendido (conhecido como Angular HTML), agiliza o desenvolvimento e torna a estrutura mais compreensível para os desenvolvedores. Além disso, recursos como o Angular CLI (Command Line Interface) facilitam a configuração inicial do projeto, o gerenciamento de dependências e a criação de componentes, agilizando o processo de desenvolvimento. Outro diferencial do Angular são as diretivas (instruções) que tornam seu uso mais simples e rápido. Alguns exemplos de diretivas:
<br>
→ ngStyle: usada para definir estilos CSS dinamicamente com base em valores no componente;<br>
→ ngModel: é usada para estabelecer ligação bidirecional entre um elemento de entrada de formulário HTML e uma propriedade do componente.<br>
→ ngIf: esta diretiva permite que você mostre ou oculte um elemento com base em uma condição;<br>
→ ngFor: usada para repetir elementos com base em uma coleção de dados.<br>


Instalação & Configuração

Obs: Para instalar o Angular é necessário que o node.js esteja instalado. 
Passo a passo:

Windows:
Baixe o instalador no site https://nodejs.org/ e execute o instalador.

Linux:
sudo apt update
sudo apt install nodejs
sudo apt install npm

MacOS:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install node

Em seguida, abra o terminal e execute:

1. Instalar o Angular CLI globalmente:
   npm install -g @angular/cli

2. Criar um novo projeto Angular:
   ng new nome-do-projeto
   
3. Navegar para o diretório do projeto:
   cd nome-do-projeto
   
4. Iniciar o servidor de desenvolvimento:
   ng serve
   
5. Acesse o aplicativo no navegador:
   Abra o navegador e vá para http://localhost:4200/ 

6. Instale bibliotecas se necessário:
npm install nome-da-biblioteca

Estes são os passos básicos para instalar e criar um projeto Angular, agora é necessário programar o conteúdo do site.

Getting Started

Ao criar-se um projeto Angular a partir do Angular CLI, haverá diversos diretórios diferentes dentro dele, sendo o principal deles o diretório src, onde ficarão a maioria dos arquivos que compõem o seu aplicativo. A partir disso, é possível construir a sua aplicação em Angular, que terá uma grande vantagem em relação a uma aplicação em puro Javascript, pois, facilitará a criação de Single Page Applications (SPA).
No mundo real, essa é a principal funcionalidade de se criar uma aplicação com a utilização de frameworks como o Angular, pois, além de facilitarem o desenvolvimento de SPAs, já que não é necessário programar todas as funcionalidades que as compõem, fazem com que o usuário tenha uma melhor experiência enquanto usa a página, pois, a velocidade e fluidez com que as informações são modificadas, devido ao fato de as informações já estarem na máquina do usuário e o navegador estar só se adequando às novas circunstâncias nas quais as informações são requisitadas, fazem com que a pessoa que utiliza a página tenha uma experiência muito melhor do que se o Angular não estivesse sendo utilizado. 
Para demonstrar como o Angular pode ser utilizado no mundo real, uma simples função de busca em uma página de um PetShop fictício foi desenvolvida pelo grupo: link_do_github.com
Ferramentas similares

Svelte
Linguagem: Javascript
O Svelte é um compilador utilizado para construir interfaces web, assim como React, Angular e Vue.js. Foi criado em 2016 por Rich Harris, e tem a proposta de ser mais performático, fácil de aprender e utilizar, possuindo uma alta curva de aprendizagem, além da sintaxe simples e intuitiva. Enquanto o Angular é um framework de aplicativos, o Svelte está mais alinhado com um kit de ferramentas de interface do usuário. Embora você possa criar um aplicativo com o Svelte, você está reunindo diferentes bibliotecas, pacotes e muito mais para obter algo semelhante ao Angular.

Angularjs
Linguagem: Javascript
AngularJS é um framework JavaScript de código aberto adequado para desenvolvimento web front-end. Assim como o Angular foi desenvolvido pela Google. Sua intenção é facilitar o desenvolvimento de aplicativos de página única. [Em vez de permitir que um servidor da Web carregue novas páginas inteiras, SPAs (aplicações de página única) interagem com o usuário reescrevendo dinamicamente os dados, buscando o mesmo do servidor da Web].
