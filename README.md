# Projeto Desenvolvido em Aula

### - Compilando a imagem ( conversao-temperatura )
``$ docker image build -t conversao-temperatura src/. ``

### - Rodando a imagem em um container na porta 8080 ( CONVERSAO )
``$ docker run -d -p 8080:8080 --name CONVERSAO conversao-temperatura``