# Projeto-Proz
Criação de EC2

Projeto criar Instancia EC2, Conectar usando SSH, Criar um Volume Elastic Block Store e anexar Instância, Criar um arquivo, Exploração de recursos


1- Instância EC2 

A seguir serão mostrado prints de como foi criada a instância no console da AWS.

<a href="https://postimg.cc/gr4yYG6H" target="_blank"><img src="https://i.postimg.cc/QxZfJt8w/1.png" alt="1"/></a><br/><br/>
<a href="https://postimg.cc/F7BjLGpf" target="_blank"><img src="https://i.postimg.cc/g2Y41T6K/2.png" alt="2"/></a><br/><br/>

Nomeando a instância, escolhendo a AMI e o Tipo de instância.

<a href="https://postimg.cc/xJnH2ZfZ" target="_blank"><img src="https://i.postimg.cc/76TNgvpq/3.png" alt="3"/></a><br/><br/>

Criando o Par de Chaves.

<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/hP8pyBhj/4.png" alt="4"/></a><br/><br/>

Finalizando a criação da Instância.

<a href="https://postimg.cc/dhZGmdN5" target="_blank"><img src="https://i.postimg.cc/YCb87z6B/5.png" alt="5"/></a><br/><br/>

Sucesso na instalação.

<a href="https://postimg.cc/2q4vgYDv" target="_blank"><img src="https://i.postimg.cc/BvzgLZ7h/6.png" alt="6"/></a><br/><br/>
<a href="https://postimg.cc/Zvqd9yyF" target="_blank"><img src="https://i.postimg.cc/prfY6fW7/7.png" alt="7"/></a><br/><br/>


2- conexão SSH:

Para conseguirmos acessar remotamente a instância pelo windows é preciso a instalação do software Putty.

Precisamos do IP público da instância para conseguir acesso através do Putty

<a href="https://postimg.cc/TyJSfpMJ" target="_blank"><img src="https://i.postimg.cc/zfs1wgx6/9.png" alt="9"/></a><br/><br/>

Inserindo o IP Público

<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/FR0XTHqR/10.png" alt="10"/></a><br/><br/>

Utilizando a Chave Privada

<a href="https://postimages.org/" target="_blank"><img src="https://i.postimg.cc/yxB4tz4T/11.png" alt="11"/></a><br/><br/>

Acesso a Instância

<a href="https://postimg.cc/ZvCD8H9w" target="_blank"><img src="https://i.postimg.cc/90p5jNcH/12.png" alt="12"/></a><br/><br/>


3- Criar Volume Elastic Block Store e anexar a Instância:

Criando o Volume Elastic Block Store.

<a href="https://postimg.cc/B8wFLfFP" target="_blank"><img src="https://i.postimg.cc/85TmY1P4/15.png" alt="15"/></a><br/><br/>
<a href="https://postimg.cc/4779p2vL" target="_blank"><img src="https://i.postimg.cc/wvFQ8S1p/16.png" alt="16"/></a><br/><br/>


Volume criado.

<a href="https://postimg.cc/sBTKDLKv" target="_blank"><img src="https://i.postimg.cc/B60zN9Kc/17.png" alt="17"/></a><br/><br/>

Como Anexar o volume criado a uma Instância.

<a href="https://postimg.cc/XGRyLKQV" target="_blank"><img src="https://i.postimg.cc/PJxzt2D8/18.png" alt="18"/></a><br/><br/>

Volume Anexado a Instância Meu Servidor WEB.

<a href="https://postimg.cc/CZfDWLdM" target="_blank"><img src="https://i.postimg.cc/BvmgPj0F/19.png" alt="19"/></a><br/><br/>


4- Criar Arquivo na Instância

<a href='https://postimg.cc/QFsm3714' target='_blank'><img src='https://i.postimg.cc/2SLKnF6D/Captura-de-tela-2024-11-25-191419.png' border='0' alt='Captura-de-tela-2024-11-25-191419'/></a>


5- Explorando Recursos

<a href='https://postimg.cc/qh3Q0HM0' target='_blank'><img src='https://i.postimg.cc/Kz9WPm6K/Captura-de-tela-2024-11-25-192449.png' border='0' alt='Captura-de-tela-2024-11-25-192449'/></a>



