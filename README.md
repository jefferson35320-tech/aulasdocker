# aulasdocker
para aulas git docker

1 - Inicie a docker engine (no windows - ligue docker desktop)
2 - criem os volumes primeiro
docker volume create wp_data
docker volume create db_data

3 - na pasta, rode o comando:
docker compose up -d

4 - Se tiver algum conflito, mate o container que está conflitando e depois rode:
docker compose down

5 - Por ultimo, rode:
docker compose up -d

6 - Para acessar o wordpress, vá no browser, crie uma tab nova e digite:
http://localhost:8080

7 - Como primeiro acesso, selecione seu idioma (no caso, Português do Brasil)

8 - Defina um usuário (admin) e uma senha - exemplo: fiec2026
Confirme tickando na opçao (Continuar com senha fraca)

9 - Pronto! Agora é só clicar em acessar com seu usuário e senha!


