# Facebook-DIO-Phising-Projeto
## Ferramentas.
###  * Kali Linux.
###  * Setoolkit.
Obs. Foram realizadas algumas alterações necessárias para realização do projeto.

## Preparação para o Phising no Kali Linux.

 1 - Para encontrar o nnúmero do IP utilizaremos o Comando ''' ifconfig '''. 
 
 2 - Após Localizarmos o IP iremos realizar o scan para obtermos os host e seus respectivos IP, para esta tarefa utilizamos o comando 
 nmap -v seguido do número do IP, porém no ultimo octeto devemos substitui-lo por 0/24, dessa forma conseguirimos obter os IPs de potênciais alvos 
 dentro da rede a qual estamos logado.

## Iniciando Phising no Kali Linux.

 1 - Devemos entra no modo root, para tal devemos utilizar o comando sudo su.
 
 2 - Neste momento estamos no modo root, porém devemos utilizar o setoolkit que irá nos auxiliar com algumas ferramentas para a realização da 
 tarefa, então devemos executar o comando setoolkit.
 
 3 - Dentro do setoolkit devemos selecionar a opção 1.

![Imagen 1](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/4856f372-092f-48ff-825e-2296979bb0d6)

 4 - Agora iremos escolher a opção 2 Website Attack Vectors.

![imagem 2](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/8c26176d-da37-444a-a8fb-7cceee3f0911)

 5 - Neste momento iremos escolher a opção 3 Credential Harvester Attack Method, pois nossa intenção é obter os dados de Login e Senha.

![imagem 3](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/3239675e-8269-4ae9-9c9f-f067758dd41f)

 6 - Neste ponto realizamos a alteração para realização do projeto pois optamos pela opção 1 (Web Templates).

![imagem 4](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/1e552001-8d65-413f-ad37-e4924eb369b7)

 7 - Neste ponto iremos utilizar o número do IP que foi obtido em nossa pesquisa de possiveis alvos, pois iremos introduzir logo em seguida ao campo que esta oculto.

![Imagem 5](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/1a579aa7-f5ed-48bf-bb81-142766e4cebc)

 8 - Agora vamos escolher a opção 2, pois iremos tentar obter o Login e Senha do Google do nosso alvo.
![imagem 6](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/6650e87d-adc8-4c84-8fef-efe957734dc3)

 9 - Pronto já configuramos o nosso Phising utilizando o setoolkit.

![imagen 7](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/5fd81b79-875f-42bc-bf0a-d7e91e43bc4b)

## Colhendo os frutos.
 Nosso Phising está pronto e esperando nosso alvo.

![Imagem 8](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/4568d9e6-2fdb-4292-aefe-81d74146ff9d)

 O alvo tentará realizar o Login usando suas credencias, neste momento nosso phising irá realizar a obtenção dos dados que buscamos.
![Senha Obtida](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/1d92075b-e86c-4ed1-91ba-d77e3b69eb91)

 Por fim o alvo será redirecionado a pagina autentica do Google sem se dar conta que vou Hackeada.
![Imagem 10](https://github.com/elvys-santos/Facebook-DIO-Phising-Projeto/assets/110802178/e73ee8d1-4475-446e-93f7-827b6a6e2008)









