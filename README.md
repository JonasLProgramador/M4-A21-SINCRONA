<!DOCTYPE html>
<html lang="pt-BR">
<body>
    <h1>📦 Projeto da aula 21 do modulo 4 utilizando  Node.js com Express</h1>
    <p>Este projeto é uma aplicação de backend simples utilizando Node.js e Express para gerenciar mensagens.Realizado durante a aula sincrona, ele permite criar, atualizar, listar e deletar mensagens através de uma API REST.</p>
    <h2>🚀 Visão Geral</h2>
    <p>A aplicação permite a gestão de mensagens através de uma API RESTful. Cada mensagem tem um ID único gerado pelo <a href="https://www.npmjs.com/package/uuid">UUID</a>, além de um nome, conteúdo e a hora de criação. As operações suportadas incluem criação, leitura, atualização e exclusão de mensagens.</p>
    <h2>📋 Funcionalidades</h2>
    <ul>
        <li>📝 <strong>Criar Mensagem:</strong> Adiciona uma nova mensagem ao sistema.</li>
        <li>📄 <strong>Listar Mensagens:</strong> Retorna todas as mensagens armazenadas.</li>
        <li>🔄 <strong>Atualizar Mensagem:</strong> Atualiza o conteúdo de uma mensagem específica pelo ID.</li>
        <li>🗑️ <strong>Deletar Mensagem:</strong> Remove uma mensagem específica pelo ID.</li>
    </ul>
    <h2>🛠️ Tecnologias Utilizadas</h2>
    <ul>
        <li><a href="https://nodejs.org/">Node.js</a> - Ambiente de execução JavaScript no servidor.</li>
        <li><a href="https://expressjs.com/">Express</a> - Framework minimalista para Node.js para construção de APIs.</li>
        <li><a href="https://www.npmjs.com/package/uuid">UUID</a> - Biblioteca para geração de identificadores únicos universais.</li>
    </ul>
    <h2>📂 Estrutura do Projeto</h2>
    <pre>
        node-express-messages/
        │
        ├── server.js           # Código principal do servidor
        ├── Message.class.js    # Classe para criação e gerenciamento de mensagens
        ├── package.json        # Dependências e scripts do projeto
        └── ...
    </pre>
    <h2>📦 Dependências</h2>
    <ul>
        <li><a href="https://expressjs.com/">Express</a> - Framework minimalista para Node.js para construção de APIs.</li>
        <li><a href="https://www.npmjs.com/package/uuid">UUID</a> - Biblioteca para geração de identificadores únicos universais.</li>
    </ul>
    <h2>🔧 Como Executar o Projeto</h2>
    <p>Siga os passos abaixo para clonar e executar o projeto em seu ambiente local:</p>
    <ol>
        <li>Clone o repositório:
            <pre><code>git clone https://github.com/JonasLProgramador/node-express-messages.git</code></pre>
        </li>
        <li>Navegue até a pasta do projeto:
            <pre><code>cd node-express-messages</code></pre>
        </li>
        <li>Instale as dependências:
            <pre><code>npm install</code></pre>
        </li>
        <li>Inicie o servidor:
            <pre><code>node server.js</code></pre>
        </li>
        <li>Acesse as rotas da API via Postman ou qualquer cliente de API na URL <a href="http://localhost:3090" target="_blank">http://localhost:3090</a>.</li>
    </ol>
    <h2>📝 Licença</h2>
    <p>Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo <code>LICENSE</code>.</p>

</body>
</html>
