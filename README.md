# Projeto_Git
Projeto de GitHub - Larissa Isabel e Maria Luiza 

<h1>1º passo: Criar um repositório no GitHub </h1>
<br>
<img src = "https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/7d6ca208-5f55-4ad1-8919-7e844ead4e4c.jpeg"> 
<br>
- Apertar no botão verde "New"
<br>
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/859ae489-75ab-4247-b5ee-1e145bb0a0da.jpeg">
<br>
- Adicionar as informações e apertar no botão "Create repository"
 <br> 
<img src = "https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/935bb63f-f12e-4ed0-92ba-19ef3a1339d9.jpeg">
<img src = "https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/c2d158a0-7624-46a5-b55c-8442043dd0b4.jpeg">
- Pronto, repositório criado.
<br>
<h1>2º passo: Criar a pasta do projeto </h1>
<br>
<img src = "https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/e29a41af-443b-4eda-9c48-c97c811f4392.jpeg">
<br>
- Com a pasta já criada, apertar com o botão direito e clicar em "OPEN GIT BASH HERE" para iniciar os comandos 
<br>
<img s-rc = "https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/36a1a083-5357-468e-827a-14ede8481f8a2.jpeg">
<br>
- Após isso, o prompt do git bash vai abrir, e o 1º código utilizado vai ser: 

<b>git init</b>: Inicia o git. 
<br>
<img src = "https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/7ef4848d-879a-460f-a275-286460a3006e.jpeg">
<br>
- Assim que iniciar o git, uma pasta oculta ".git" vai aparecer. Depois, vamos começar a criar os arquivos do nosso projeto.
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/d741391d-c298-42f7-a00a-b3f141c6c50e.jpeg">
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/ac945d84-d0bd-4b69-9410-27bf4915954b.jpeg">
<h1>3º passo: Configurações no Git Bash</h1>
- Os primeiros códigos que devemos utilizar são: 
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/5ea67fd9-50cd-4e2f-bb53-e3971937bbbd.jpeg"> 
 + Devemos linkar nosso github com o git bash, e por isso usamos esses 2 códigos, que conectam nosso nome de usuário e nosso email do github. 
- O próximo código é o '<b>git status</b>': ele mostra o que temos de alteração na pasta, tudo que foi feito de novo ou modificado. 
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/7b2699b7-36db-432a-91b7-2a99f4e7854d.jpeg">
- O próximo passo é usar o comando: '<b>git add .</b>' que adiciona ao projeto todas essas alterações, e após isso, um '<b>git status</b>' novamente
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/23dbd074-2fac-4a5c-a2e5-4ed9fa66c6cd.jpeg">
- Em seguida, usaremos os comandos '<b>git commit -m</b> para salvar com uma mensagem, e depois '<b>git log</b>' que mostra o que salvamos nesse commit
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/05e7a75f-bcb5-4b7e-8ca9-c49c1f2f59a0.jpeg">

<h1>4º passo: juntar o que foi feito no Git Bash com o repositório no GitHub</h1>
- O primeiro passo é ir no nosso repositório já criado e em "CODE" copiar o link do rpositório
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/7e6cd402-b192-401a-b6aa-ef31c0c1a087.jpeg">
- Após isso vamos usar o comando '<b>git remote add origin + link do repositório</b>' e depois o comando '<b>git pull --allow-unrelated-histories + link do repositótio</b>'
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/5c5fb5f3-3052-4c30-9686-12f7917e39c0.jpeg">
- Assim que colocarmos o 2º código, uma tela de confirmação vai aparecer:
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/2bddec38-7093-4720-bbb3-84285f9cf7cf.jpeg">
- Para confirmar, devemos apertar ESC, depois usar o código '<b>:wq!</b>' e apertar ENTER
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/0081df09-7038-480d-8e2e-dc8f7de89cbe.jpeg">
- E então voltaremos para a parte dos códigos
<img src ="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/d79c4516-7dcb-456b-9b01-5e1dddfae88b.jpeg">
- Agora usareos os códigos '<b>git pull</b>', '<b>git pull --verbose</b>' e '<b>git add . </b>' para concluir essa parte
<img src="https://github.com/MaluAlmeida/Projeto_Git/assets/150203502/d79c4516-7dcb-456b-9b01-5e1dddfae88b.jpeg">
<img src=".jpeg">
- E pronto, os dois estão juntos agora.
