# prova1computacaonuvem
Nome: Emerson Moura Gama 
RA:b3a4af784da9afb4c5f7

## O que fiz

Executei uma pagina web em um conteiner Docker chamado treinamento.
Usei a imagem nginx:alpine e a porta 8083 do ambiente.

## Verifcação do contêiner

docker ps
CONTAINER ID   IMAGE          COMMAND                  CREATED              STATUS              PORTS                                     NAMES
086b746b272e   nginx:alpine   "/docker-entrypoint.…"   About a minute ago   Up About a minute   0.0.0.0:8083->80/tcp, [::]:8083->80/tcp   treinamento

## Teste da página

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Treinamento</title>
</head>
</body>
<h1>Treinamento ativo</h1>
</body>
</html>

## Explicação

Com minhas palavras, qual é a diferença entre a imagem nginx:alpine e o contêiner treinamento ?Para que serviu o mapeamento 8083:80?

nginx:alpine é o modelo com o software necessário; comunicado é o contêiner criado e executado a partir dessa imagem.
 Mapeamento de portas: 8083:80 associa a porta 8083 do ambiente à porta 80 em que o Nginx atende dentro do contêiner.
 
