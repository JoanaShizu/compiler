<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
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

  <h2>Licença</h2>
    <p>Este projeto está licenciado sob a licença MIT.</p>

</html>
