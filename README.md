<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
    <div class="container">
        <h1>LL(1) Parser</h1>
        <p>Este projeto implementa um analisador sintático LL(1) que lê uma tabela de parsing e um arquivo de entrada, realizando a análise sintática com base nas regras definidas na tabela.</p>

<h2>Estrutura do Projeto</h2>
        <ul>
            <li><code>index.js</code>: Script principal que executa o analisador sintático.</li>
            <li><code>table.csv</code>: Arquivo CSV contendo a tabela de parsing.</li>
            <li><code>input.txt</code>: Arquivo de texto contendo a entrada a ser analisada.</li>
            <li><code>package.json</code>: Arquivo de configuração do npm.</li>
        </ul>

<h2>Requisitos</h2>
        <ul>
            <li>Node.js (versão 10 ou superior)</li>
            <li>npm</li>
        </ul>

<h2>Uso</h2>
        <ol>
            <li>Coloque a tabela de parsing no arquivo <code>table.csv</code>. A tabela deve estar no formato CSV com a primeira coluna representando os não-terminais e as outras colunas representando os terminais.</li>
            <li>Coloque a entrada a ser analisada no arquivo <code>input.txt</code>.</li>
            <li>Execute o analisador:
                <pre><code>npm start</code></pre>
            </li>
            <li>O script irá ler a tabela de parsing e a entrada, realizar a análise sintática e exibir o resultado no console.</li>
        </ol>

<h2>Estrutura do Código</h2>
        <h3>index.js</h3>
        <p>Importa as dependências necessárias (<code>fs</code>, <code>csv-parser</code>, <code>path</code>). Define funções para:</p>
        <ul>
            <li>Ler e parsear o arquivo CSV (<code>parseCSV</code>).</li>
            <li>Ler o arquivo de entrada (<code>readInput</code>).</li>
            <li>Transformar a tabela CSV em um formato adequado para o parser (<code>parseTable</code>).</li>
            <li>Realizar a análise sintática (<code>parseInput</code>).</li>
        </ul>
        <p>A função <code>main</code> orquestra a leitura dos arquivos, o parsing da tabela e da entrada, e a execução da análise sintática.</p>

<h3>package.json</h3>
        <p>Define as dependências do projeto, incluindo <code>csv-parser</code> para leitura do arquivo CSV. Define o script <code>start</code> para execução do projeto.</p>

<h2>Exemplos de Arquivos para Testes</h2>
        <p>Este repositório inclui exemplos de arquivos para facilitar os testes do analisador sintático:</p>
        <ul>
            <li><code>table.csv</code>: Contém a tabela de parsing usada pelo analisador.</li>
            <li><code>input.txt</code>: Contém a entrada a ser analisada pelo analisador.</li>
        </ul>
    </div>
</body>
</html>
