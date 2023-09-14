Підняти через <code>Dockerfile</code>:<br>
<code>docker build -t my-todo .</code><br>
<code>docker run --name=my-todo -dp 3000:3000 my-todo</code><br>
<code>docker rm -f my-todo</code><br>

Підняти через <code>compose.yaml</code>:<br>
<code>docker compose up -d</code><br>
<code>docker compose logs -f app</code><br>
<code>docker compose exec -it app sh</code><br>
<code>docker compose stop</code><br>
<code>docker compose rm</code><br>