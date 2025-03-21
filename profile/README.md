## Olá! Nos somos a equipe Hermes👋

## Nosso Objetivo 
  Nosso projeto tem como objetivo trazer uma maior gama de entreterimento para os alunos durante o periodo livre na escola, como nos intervalos e ate em  eventos na instituição,
 e mesmo assim comtribuir para o meio ambiente e para o arrecadamento de doeações para os mais necessitados, onde os creditos que serao usados nos arcades serao dados de acordo
 com as doacões dos alunos ou a contribuição nos projetos de reciclagem da instituição.


## Como ele sera feito
Nosso projeto visa a reciclagem e o reaproveitamento de recursos, entao nossa intensão e reutilizar recursos que estarian sem uso ou que apresentao mau funcionamento para a construção de nosso arcades.
Nossos controles possuirão botoes padroes de arcade, mas o seu cabeamento sera feita da placa de um teclado antigo, onde serao soldados fios na placa do teclado e eles serão conectados em cada botão.
O sistema funcionara em um Notebook antigo, onde nele rodara os jogos e o servidor do projeto, neste notebook estara conectado a placa dos botões do arcade e uma placa WeMos D1 que funcionara como a "ficheiro"
e nele um pequeno teclado para arduino e uma pequena tela LCD de arduino, no teclado o aluno ira digitar seu RM(Registro de Matricula) e o WeMos ira receber este numero e ira puxar da API do projeto os dados do aluno,
como o nome e quantos creditos ele possui, apos isto ira aparecer na pequena tela LCD o nome de usuario e os creditos disponiveis, logo abaixo aparecera uma pergunta "voce que jogar?sim:* Não:#" se o aluno clicar em 
"sim" sera discontado de seus creditos a vez jogado por meio de uma API, apos a placa WeMos fara outra requisição a API puxando os dados atualizados do aluno  e fazendo todo o processo para liberar o credito novamente
para o aluno. quando o aluno clicar em não serao apagados os dados do aluno da placa WeMos e retornara ao inicio do processo onde ela espera o aluno digitar seu RM(regtistro de Matricula)
