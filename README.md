# 🧮 Calculadora Interativa com Docker

Este é um projeto simples de uma calculadora feita com **HTML**, **CSS** e **JavaScript**, empacotada em um container **Docker** 

## ✨ Funcionalidades

- Interface visual e intuitiva  
- Suporte às principais operações:
  - Soma
  - Subtração
  - Multiplicação
  - Divisão
- Botão de limpar (`C`)
- Resultado dos cálculos com o botão `=`

## 🛠 Como rodar o projeto

### 1. Clonar o repositório

```bash

git clone https://github.com/dudacapelini/Atv-Pedro-Calculadora-Docker.git

cd Atv-Pedro-Calculadora-Docker

```

### 2. Construir a imagem Docker

```bash

docker build -t calculadora-docker .

```

### 3. Rodar o container

```bash

docker run -p 8080:8080 calculadora-docker

```

### 4. Acessar a aplicação

Abra o navegador e vá até:

```
http://localhost:8080

```

## 🐳 Requisitos

- Docker instalado na máquina

## 📂 Estrutura do projeto

```

calculadora-docker/
├── index.html
├── style.css
├── Dockerfile
├── package.json
└── README.md

```


Criado pela: Maria Eduarda Capelini Pereira
