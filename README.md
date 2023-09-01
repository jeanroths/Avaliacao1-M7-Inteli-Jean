# Avaliacoes-M7-Inteli
Avaliações do Módulo 7

## Backend
Criei um diretorio no backend /app, instalei os requirements, dei o pip install do requirements, e copiei para o diretorio /app e coloquei o que deve ser excutado na linha de comando do backend com a porta 3000, alem disso consegui subir esse dockerfile como jeanrothstein/backprova, então é so dar um docker pull jeanrothstein/backprova.

## Frontend
Usando node:18 de base da imagem, eu crio o diretorio /app, coloco o package.json para ser lido la, tento rodar o npm install para instalar dependencia do node, dou o npm run build expondo a porta 8000 e mando a linha de comando para ser executada com npm start.

## Docker-compose
Apenas criei as imagens do front e do backend colocando portas 3000 e 8000 para back e front respectivamente, colocando o nome dos containers.

### Comentário
Tentei subir dockerfile do front mas deu um erro: ERROR: failed to solve: process "/bin/sh -c npm install" did not complete successfully: exit code: 254