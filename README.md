# prova1computacaonuvem
Nome: Emerson Moura Gama 
RA:b3a4af784da9afb4c5f7

## O que fiz

Executei uma pagina web em um conteiner Docker chamado treinamento.
Usei a imagem nginx:alpine e a porta 8083 do ambiente.

## Verifcação do contêiner

## Teste da página

## Explicação

Com minhas palavras, qual é a diferença entre a imagem nginx:alpine e o contêiner treinamento ?Para que serviu o mapeamento 8083:80?

 Imagem e contêiner: nginx:alpine é o modelo com o software necessário; comunicado
é o contêiner criado e executado a partir dessa imagem.
 Mapeamento de portas: 8083:80 associa a porta 8083 do ambiente à porta 80 em que
o Nginx atende dentro do contêiner.
 Evidência da página: A saída do curl deve conter “Comunicado interno disponível”.
docker ps comprova a execução do contêiner, mas não demonstra sozinho o conteúdo da
página.
