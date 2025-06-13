# Template de desenvolvimento de websites React

> Quer desenvolver em React sem ter que instalar dezenas de coisas em seu computador? Este é seu repositório!!!

### Avisos

Usar apenas para desenvolvimento local. Adaptações são necessárias caso deseje publicar o website em produto.

## 💻 Pré-requisitos

Antes de começar, verifique que sua máquina possua:

- Docker

## 🚀 Instalando

Com o terminal (ou prompt de comando), entre na pasta do repositório e digite o seguinte comando:

```
docker compose up --build
```

Se o processo acabar com sucesso, você poderá acessar o website resultante em

```
http://localhost:5173/
```

Caso esteja utilizando o Windows, não se esqueça de antes inicializar o Docker Desktop ou similares.

## ☕ Usando

Altere o diretamente os arquivos de código-fonte na pasta `src`. O sistema suporta *hot reload*, ou seja, basta salvar seu código-fonte que a página do navegador será atualizada automaticamente.

Se quiser adicionar uma nova biblioteca ao projeto, edite o arquivo **package.json** de forma apropriada. Pode ser necessário reiniciar o processo de `docker compose up --build` caso uma nova biblioteca seja adicionada ao projeto.

