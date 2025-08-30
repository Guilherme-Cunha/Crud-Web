Para iniciar um servidor local e rodar um projeto web de forma simples, você pode seguir estes passos gerais:

Instale um servidor web local: Existem várias opções para isso, mas uma das maneiras mais simples é usar o Python, que vem com um servidor web embutido. Certifique-se de ter o Python instalado no seu sistema.

Navegue até o diretório do seu projeto: Abra um terminal ou prompt de comando e navegue até o diretório onde o seu projeto está localizado.

Inicie o servidor web: Dependendo do seu ambiente de desenvolvimento, você pode usar diferentes comandos para iniciar o servidor.

Se você estiver usando Python 3, você pode usar o seguinte comando no terminal:
    python -m http.server

Isso iniciará um servidor web na porta padrão 8000. Se você deseja usar uma porta diferente, especifique o número da porta após o comando (por exemplo, python -m http.server 8080 para usar a porta 8080).

Se você estiver usando Python 2, pode usar o seguinte comando:
    python -m SimpleHTTPServer

Isso iniciará um servidor web na porta padrão 8000.

Acesse o projeto no navegador: Abra um navegador da web e vá para http://localhost:8000 (ou a porta que você especificou, se diferente). Você deve ver o seu projeto sendo executado localmente.

Com a pasta do projeto na área de trabalho, o caminho deverá ficar assim:
    http://localhost:8000/Desktop/Projeto%20CRUD%20Web/Login.html
	
Um usuário é automaticamente cadastrado ao iniciar a aplicação
    Usuário: adm
	Senha: 123
