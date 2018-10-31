
<h3>Tarefa: Desenvolver 4 Servers integrados utilizando Docker. A aplicação consiste em: Um banco de dados, uma fila ou ftp para servir os dados, um cosumidor para consumer os dados da fila/ftp e uma API para consultar os dados do banco de dados.</h3>

 

Abaixo, detalhes e obrigações de cada Server.

 

<h3>Server1</h3>
 BANCO DE DADOS: Local onde os dados da lista serão armazenados pelo consumer.

*O banco de dados deve ser nosql

 

<h3>Server2</h3>
 FTP ou AMQP: Local onde os dados que serão consumidos devem estar.

*Os dados devem estar no formato CSV ou Json. Em anexo arquivo com os dados para o teste.

 

<h3>Server3</h3>
 NODEJOB-CONSUMER: Consumidor responsável por processar os dados do Server2 e armazenar no banco de dados

 

<h3>Server4</h3>
 NODE-SERVICE: WebService RESTful

*API para listar todos os dados armazenados na Base de Dados (Server1)



Prazo: 4 dias.
