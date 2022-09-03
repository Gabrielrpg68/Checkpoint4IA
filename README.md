# Checkpoint4IA

<h3> Gabriel Jesus Dantas rm88737 </h3>
<h3> Guilherme Beck Lobo  rm87531</h3>

### Resumo
Projeto criado para validar um acesso com o tag rfid, onde, depois do usuario enconstar sua TAG RFID o arduino ira validar o codigo de acesso e depois enviar para o NODE-RED. No node-red, nós temos um fluxo que irá receber o valor da tag do usuario e com um botão esse valor ira ser exibido para o usuario pelo node-red dashboard e outro botão exemplificando o usuario sendo liberado girando um motor, simulando uma catraca. Também criamos uma conexão com o Telegram, bot_father.

### Como rodar o projeto

Baixe os arquivos do projeto que estão nesse repositório.
Com o app do arduino abra o arquivo CheckPoint4.ino. Depois abra o cmd e digite node-red, com o node_red aberto localmente importe o arquivo .json do repositorio, para funcionar você tera de baixar duas bibliotecas no node-red, node-red-dashboard e node-red-node-serialport.
