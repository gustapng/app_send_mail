## 🔧 Projeto Send Mail - Enviar e-mail usando SMTP

Esse foi meu primeiro projeto utilizando a biblioteca PHPMailer, esse tipo de funcionalidade é muito aplicada em soluções Front-end e com toda certeza será um conhecimento que eu aplicarei em diversos projetos futuros.

## 📁 Acesso ao projeto

Faça um clone do repositório para sua maquina:
git clone https://github.com/gustapng/app_send_mail.git

## 🛠️ Configurar o projeto!

**. No arquivo processa_envio.php faça as seguintes alterações <br>**

![code](https://user-images.githubusercontent.com/102172136/191755978-d4aa5d4c-f9da-48a1-b4fd-85906c61255e.png)

Como ativar senhas de apps externos

Aqui vai uma informação importante sobre o envio de e-mails por meio do Gmail. Atualmente a opção de "apps menos seguros" não está mais autorizada pelo Google. Agora precisamos gerar uma senha exclusiva para este fim, mas não se preocupe, é só seguir as orientações deste artigo!

Para configurar uma senha exclusiva para o seu projeto, acesse a conta de e-mail do Gmail que será utilizada em seu projeto e siga os passos:

1 - Clique na opção "Gerenciar sua Conta do Google":<br>
![2022-08-04_20-34-53-bbb33a9b80228f7f1ad166a929810272](https://user-images.githubusercontent.com/102172136/191757273-634d6450-4fae-4121-acab-f7f706ba241b.png)
<br>

2 - Clique na opção "Segurança":<br>
![2022-08-04_20-34-53-d35a359e64762026773a6bd41866ea84](https://user-images.githubusercontent.com/102172136/191757348-99a03dfd-04fc-4949-bd12-189864fa47cc.png)
<br>

3 - Ative a opção de "Verificação em duas etapas":<br>
![2022-08-04_20-34-53-1d786d00a3f0d9244c42e49f187d723a](https://user-images.githubusercontent.com/102172136/191759020-1e971e53-0e92-47f1-ab39-145f6acb97ec.png)
<br>

4 - Clique na opção "Senhas de app":<br>
![2022-08-04_20-34-53-323381cac79a9285d10e452f4e97c4b3](https://user-images.githubusercontent.com/102172136/191757520-217b803b-59af-4b6a-b33e-2365edec5984.png)
<br>

5 - Clique na opção "Selecione o app e o dispositivo para o qual você quer gerar a senha de app" e escolha a opção "Outro":<br>
![2022-08-04_20-34-54-93093c080f7eda0d32ba8246f093a500](https://user-images.githubusercontent.com/102172136/191757618-2433efcd-b915-4c5d-b269-d3a013ec353c.png)
<br>

6 - Defina um nome (pode ser qualquer nome) e depois clique em "gerar"<br>
![2022-08-04_20-34-54-b2a14e8364087dd4e7923195823baf34](https://user-images.githubusercontent.com/102172136/191757701-a0d7ecde-3d6a-47e0-98f4-10e9567a7fe6.png)
<br>

7 - A senha será gerada, basta copiá-la:<br>
![2022-08-04_20-34-54-262ad329e721903ec0023464447ba3e5](https://user-images.githubusercontent.com/102172136/191757806-3c64a8e3-a638-46c0-8c94-c99bb502b84c.png)
<br>

8 -  Utilize a senha copiada  no arquivo de configuração de envio de e-mail (processa_envio.php):<br>
![2022-08-04_20-34-54-d45204844c2330cac2e0cb22a459093c](https://user-images.githubusercontent.com/102172136/191758044-49b96059-e077-4d77-bd60-e241f64b8d7a.png)
<br>

## 🛠️ Rodar o projeto!
**. Utilize seu servidor Apache e abra arquivo index.html usando o LocalHost no navegador de sua preferência<br>**
**. Preencha os campos corretamente e submeta o formulário<br>**

![Captura da Web_22-9-2022_103338_localhost](https://user-images.githubusercontent.com/102172136/191762109-739280d2-c831-451b-90dc-79a7eb7a6b19.jpeg)
![Captura da Web_22-9-2022_103435_localhost](https://user-images.githubusercontent.com/102172136/191762119-276e5056-b826-49f8-aa37-fbfbb201a43f.jpeg)
**. Cheque o E-mail**
![Sem Título-1](https://user-images.githubusercontent.com/102172136/191763286-463b1fbc-c17f-4258-b31f-d8753c92d3eb.png)



