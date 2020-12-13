<div align='center'>
    <h1>Projeto Final: AnjoAumigo 🐾</h1>
    <img alt="Banner do Anjo Aumigo com imagem de uma família abraçando um gato e um cachorro" src="./assets/banner.png" width="600px">
</div>
<div align='center'>
<a href="https://github.com/elvasthaisa/projeto-adocao-pets/network"><img src = https://img.shields.io/github/forks/elvasthaisa/projeto-adocao-pets></a>
<a href="https://img.shields.io/github/stars/elvasthaisa/projeto-adocao-pets"><img src = https://img.shields.io/github/stars/elvasthaisa/projeto-adocao-pets></a>
<img src = https://img.shields.io/github/license/elvasthaisa/projeto-adocao-pets>
<a href="https://projeto-final-thaisa.herokuapp.com/"><img src="https://img.shields.io/static/v1?label=deploy&message=heroku&color=51CBF3&style=flat"></a>
<a href="https://github.com/elvasthaisa/projeto-adocao-pets/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/elvasthaisa/projeto-adocao-pets?color=%23F29181&label=Open%20Source%20%F0%9F%92%99&logoColor=%23E9F9FB"></a>
</div>

O presente projeto é referente ao Bootcamp Back-End da {Reprograma} em parceria com o Porto Digital MINAS e tem como objetivo aplicar todo o conhecimento obtido através do curso.

## Motivação do tema escolhido
- Durante a pandemia, vi crescer o número de pets em estado de abandono e a procura de pessoas dispostas a adotá-los. Pesquisando a respeito, descobri que a OMS estima que haja no Brasil cerca de _30 milhões de animais abandonados_, sendo 10 milhões de gatos e 20 milhões de cachorros. Com a crise econômica durante o COVID-19, ainda mais animais foram abandonados por falta de suporte financeiro de seus tutores.

- Como passei também pela experiência de cuidar de uma cachorrinha retirada das ruas antes de a mesma ir a um lar definitivo, senti a necessidade de criar uma API que facilitasse a conexão dos animais abandonados, e que estivessem em lares temporários, a possíveis tutores "anjos" que tenham a disponibilidade e o carinho de cuidar desses animais com muito amor.

## 💻 Tecnologias
- [Controle de Versionamento (Git)](https://git-scm.com/)
- [JavaScript](https://www.javascript.com/)
- [Gerenciamento de pactotes (npm)](https://www.npmjs.com/) <img src="https://img.shields.io/badge/npm-6.14.8-pink">
- [Node](https://nodejs.org/en/) <img src="https://img.shields.io/badge/NodeJs-339933.svg?style=flat&logo=node.js&logoColor=white"/> 
- [MongoDB](https://www.mongodb.com/) <img src="https://img.shields.io/badge/MongoDB-444444.svg?style=flat&logo=mongoDB&logoColor=green">
- [Heroku](https://dashboard.heroku.com/) <img src="https://img.shields.io/static/v1?label=deploy&message=heroku&color=pink&style=flat"/>

🔰 Dependências 
- [Express](https://expressjs.com/pt-br/) <img alt="Express version" src="https://img.shields.io/badge/express-4.17.1-blue"/>
- [Mongoose](https://mongoosejs.com/) <img alt="Mongoose version" src="https://img.shields.io/badge/mongoose-5.10.17-blue"/>
- [Bcrypt](https://www.npmjs.com/package/bcrypt) <img alt="Bcrypt version" src="https://img.shields.io/badge/bcrypt-5.0.0-blue"/>
- [Dotenv-safe](https://www.npmjs.com/package/dotenv) <img src="https://img.shields.io/static/v1?label=dotenv-safe&message=8.2.0&color=blue&style=flat&logo=mongoose"/>
- [Jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) <img alt="jsonwebtoken version" src="https://img.shields.io/badge/jsonwebtoken-8.5.1-blue"/>
- [Nodemon](https://www.npmjs.com/package/nodemon) <img alt="Nodemon version" src="https://img.shields.io/badge/nodemon-2.0.6-blue"/>


🔰 Utilitários
- Teste de API: [Postman](https://www.postman.com/downloads/) <img src="https://img.shields.io/badge/-Postman-orange">
- Ícones: [Emojis para Github](https://gist.github.com/rxaviers/7360908)
- Paleta de cores: [Adobe Color](https://color.adobe.com/pt/)
- Criação da arte: [Canva](https://www.canva.com/)

## Como funcionará a API?

Haverá duas entidades (schemas) na inserção de dados:

😇 Anjo (tutor para o pet)

🐶 Pet em busca de lar amigo
____
## 🚥 Rotas da API 

## 🚦😇 Anjos

| Método |  Rota                              | Função                                               |
|:------:|:--------------------------------------------:| ------------------------------------------ |
| GET | `/anjos` | Lista todos os anjos com interesse para adotar |
| POST | `/anjos` | Cadastra um novo anjo com interesse para adotar |
| PUT | `/anjos/user?nome=Name&email=name@gmail.com` | Permite alteração de informações sobre o anjo |
| DELETE | `/anjos/user?nome=Name&email=name@gmail.com` | Permite deletar informações sobre o anjo |

## 🚦🐶 Pets

| Método | Rota                                    | Função                                    |
|:------:|-----------------------------------------| ----------------------------------------- |
| GET | `/pets` | Lista todos os pets disponíveis a adoção |
| POST | `/pets` | Cadastra um novo pet para adoção |
| PUT | `/pets/pets?nome=Name&tipoPet=cachorro` | Permite alteração de informações sobre o pet |
| DELETE | `/pets/pets?nome=Name&tipoPet=cachorro` | Permite deletar informações sobre o pet |

## 📃 Licença
Esse repositório está licenciado pelo **MIT License**.
____

<p align="center">
    Developed with 💜 by <b>Thaísa Elvas</b> :octocat: 
</p>
<p align="center">
    <a href="https://www.linkedin.com/in/thaisa-elvas/"><img src="https://img.shields.io/badge/-Thaísa_Elvas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/thaisa-elvas/"/>
    </a>
    <a>
    <a href="thaisaelvas@gmail.com"><img src="https://img.shields.io/badge/-thaisaelvas@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:marinamaredesign@gmail.com"/>
    </a>
</p>