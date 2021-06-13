<h1>Ecoleta ♻️</h1>
<p>Site de criação e pesquisa de pontos de coleta de resíduos para reciclagem criado pela Rocketseat para a semana Next Level Week.</p>
<div>
    <img src=".github/img1.png" alt="Página inicial do Ecoleta"/>
    <img src=".github/img2.png" alt="Página para pesquisar pontos de coleta"/>
    <img src=".github/img3.png" alt="Página para cadastrar ponto de coleta"/>
</div>
<h2>🚀 Tecnologias</h2>
<ul>
    <li><img src=".github/nodejs.png" alt="Node.js Logo" width="60px" height="60px"/> Node.js</li>
    <li><img src=".github/express.png" alt="Express Logo" width="60px" height="50px"/> Express</li>
    <li><img src=".github/sqlite.png" alt="SQLite3 Logo" width="60px" height="37px"/> SQLite3</li>
    <li><img src=".github/nunjucks.png" alt="Nunjucks Logo" width="60px" height="50px"/> Nunjucks</li>
    <li><img src=".github/nodemon.png" alt="Nodemon Logo" width="60px" height="60px"/> Nodemon</li>
</ul>

<h2>🔧 Instalação</h2>
<h3>Pré-requisitos:</h3>
<ul>
    <li>Node.js</li>
    <ol>
        <li>Vá ao site <a href="https://nodejs.org/en/download/" title="Site Node.js">https://nodejs.org/en/download/</a></li>
        <li>Escolha a versão de acordo com o seu sistema operacional.</li>
    </ol>
</ul>
<span>OBS: o NPM já vem acompanhado do Node.js.</span>
<h3>Dependências:</h3>
<ul>
    <li>Express</li>
    <li>Nodemon</li>
    <li>Nunjucks</li>
    <li>SQLite3</li>
</ul>
<h3>Para instalar as dependências:</h3>
<ol>
    <li>
        Clone o repositório:
        <code>git clone https://github.com/ana-ferreiramg/nlw-ecoleta.git</code>
    </li>
    <li>
        Use o comando:
        <code>npm install</code>
    </li>
</ol>
<h4><strong>Se houver erro na hora de instalar as dependências, siga as instruções a seguir:</strong></h4>
<p>
    Abra o CMD(ou PowerShell) como administrador e rode: <code>npm install --global --production windows-build-tools</code>
    <br/><span>(caso a instalação fique em loop cancele a operação (ctrl+c) para finalizar em lotes)</span>
</p>

Se não funcionar siga as instruções a seguir:

<ol>
    <li>Instale o Python versão 2.7.x (o node-gyp não suporta a versão 3 do Python)</li>
    <li>Configure a variável de ambiente do sistema (Path) com o caminho até o python:
        <ul>
            <li>C:\Users\{seu usuário aqui}\.windows-build-tools\python27\python.exe</li>
            <li><a href="https://medium.com/@victorromariopazdejesus/python-3-configurando-vari%C3%A1veis-de-ambiente-no-windows-10-63059c7192e6">Configurar variável de ambiente no windows</a></li>
        </ul>
    </li>
    <li>Abra o CMD(ou PowerShell) como administrador e instale o node-gyp: <code>npm install --global node-gyp</code></li>
    <li>Entre no diretório do projeto e tente instalar as dependências: <code>npm install</code></li>
</ol>
<h2>🚩 Rodar aplicação</h2>
<p>
    Dentro do diretório do projeto use o comando:
    <code>npm start</code>
    <br>
    O app vai abrir em modo de desenvolvimento.
</p>
<p>Para ver o resultado, basta abrir seu browser e acessar: <a href="http://127.0.0.1:3000/">http://127.0.0.1:3000/</a></p>
