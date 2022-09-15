<h1> Bem vindo(a) ao kit desenvolvimento concentradores </h1>
Esse kit tem o intuito de lhe auxiliar no desenvolvimento de sua aplicação para integração com os equipamentos da Companytec.
Em primeiro momento é necessário saber que existem duas possibilidade de comunicação com os equipamentos, uma através da DLL e outra através do protocolo nativo.
Caso sua intuição for trabalhar com a DLL, nesse kit há uma pasta relacionada a ela e onde encontrarás os manuais, onde é possível verificar todas as funções que a mesma possui, exemplos de softwares para a integração dela com o seu sistema e a proópria DLL.
Caso sua intuição seja trabalhar com o protocolo nativo, neste kit também há alguns exemplos em diversas linguagens demonstrando como realizar a conexão via socket com os equipamentos e os manuais para verificar quais comandos a automação irá responder.
Agora que já sabemos sobre os tipos de integração que temos, agora chegou a hora de verificar qual protocolo de comunicação utilizar caso a opção não seja trabalhar com a DLL.
Na Companytec, temos três tipos de protocolos de comunicação, o CBC, o Companytec e o Horustech.
O protocolo CBC foi desenvolvido para trabalhar com os modelos mais antigos de automação, os modelos CBC. Esses modelos foram fabricados desde a CBC01 até a CBC06, essa última parou de ser fabricada por volta do ano de 2012. Depois desse ano, a Companytec começou a fabricar os modelos Horustech e com ela, se viu a necessidade de fazer um novo protocolo, o Horustech, onde o mesmo tinha uma sintaxe diferente do antigo e também era mais robusto, corrigindo possíveis problemas do anterior.
Com essa mudança a Companytec se viu diante de um impasse, agora como tinha um protocolo novo, não tinha como fazer as softwares houses trabalharem somente com esse protocolo, pois isso iria gerar um grande transtorno para as mesmas, teriam que reescrever todo o código para se adaptar ao novo modelo, então foi aí que surgiu a ideia de fazer um terceiro protocolo, o Companytec, que nada mais é do que a sintaxe do protocolo CBC adaptado aos modelos mais atuais, ou seja, a Horustech.
Fazendo um resumo do explicado, caso sua inteção seja desenvolver um software para trabalhar com todos os modelos de automação, pode usar o protocolo CBC/Companytec, mas caso a sua intenção seja trabalhar somente com as automações mais atuais, pode realizar o desenvolvimento no protocolo Horustech.
Caso tenha alguma dúvida sobre essas quesões de integração, pode entrar em contato conosco, o telefone e whatsapp é (53) 3284-8100, skype é desenvolvimento2companytec e o e-mail é desenvolvimento@companytec.com.br, falar com Patrick Medeiros.