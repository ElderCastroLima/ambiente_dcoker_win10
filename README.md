# ambiente_php_docker_win10
Boilerplate para criação de ambiente de desenvolvimento php com docker no windows 10

1 - Baixe o docker para o windows 10. 

https://store.docker.com/editions/community/docker-ce-desktop-windows

2 - Depois de instalado execute o comando docker -v.

Se exibir a versão do docker corretamente a instalação foi concluida com sucesso.

3 - Faça o clone desse repositório para a sua máquina

4 - Utilizando o cmd ou o seu prompt preferido(eu uso o git bash) navegue para dentro da pasta que você clonou o projeto.
Certifique-se que o arquivo docker-compose.yml está na pasta.

5 -  Execute o comando docker-compose up.

6 - A primeira vez que você executar esse comando vai demorar um pouco porque será baixado para o docker as imagens do php e nginx.
nas proximas vezes que você for subir o ambimente será muito rápido pq as imagens já estão no docker.

7 - Ao finalizar basta acessar no seu browser localhost:80. Se tudo deu certo você deverá ver o informações da versão do php.

8 - Pronto seu ambiente de desenvolvimento php com docker no windows 10 já está pronto.
 
Lembrando que todas as configurações para subir seu ambiente de desenvolvimento ficam no docker-compse.yml e você pode editar como melhor quiser.


