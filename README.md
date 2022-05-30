# nameproject

## How to Use

1 Create Docker Network <br>
docker network create compose_network <br>
<br>
2 Build UI Container <br>
docker-compose -f docker-compose_p1.yml up -d --build <br>
<br>
3 Build Ngx Container
docker-compose -f docker-compose_ngx.yml up -d --build <br>




