 # Projeto criação de formulários
## Descrição
<p align="left"> Projeto de criação de formularios </p>

Tabela de Conteúdos
=================
<!--ts-->
   * [Sobre](#Sobre)
   * [Tabela de Conteudo](#tabela-de-conteudo)
   * [Tecnologias](#tecnologias)
   * [Instalação](#instalacao)
   * [Como usar](#usando)
      * [Pre Requisitos](#pre-requisitos)
   * [Tests](#testes)
   * [Features](#features)

<!--te-->


### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Python](https://www.python.org/)
- [Django ](https://www.django-rest-framework.org/)

### 🛠 Usando

#### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Python](https://www.python.org/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o Back End (localmente)

```bash
# Clone este repositório
$ git clone https://github.com/ChrisOliveir/Formul-rios_Django.git

# Crie o ambiente virtual e depois acesse-o:
$ python -m venv venv
$ source venv/bin/activate

# Ativando caso seu sistema seja Windows:
$  ./venv/Scripts/bin/activate

# Acesse a pasta do projeto no terminal/cmd
$ cd back-end-fintech

# Instale as dependências
$ pip install -r requirements.txt

# Executar os comandos para migrar tabelas para o banco de dados 
$  python manage.py makemigrations 
$  python manage.py migrate 

# Execute a aplicação em modo de desenvolvimento
$  python manage.py runserver

# O servidor inciará na porta:3333 - acesse <http://localhost:>
```

### Features
