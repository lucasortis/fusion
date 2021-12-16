# fusion
Um laboratório utilizando docker-compose

Aplicação em Django, Postgre e Nginx.

Com apenas um comando são criados 5 containers, e o Nginx garante o balanceamento de carga entre 3 containers.

Navegue até a pasta da aplicação e digite
docker-compose build

3 imagens serão criadas dentro do docker.

Digite o seguinte comando para subir os containers
docker-compose up -d

Para verificar se os containers estão rodando
docker ps -a 

E para excluir os containers
docker-compose down
