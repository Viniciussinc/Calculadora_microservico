# Calculadora em Microserviços
Testando microserviços com uma aplicação simples de calculadora, onde cada operação de cálculo, a princípio, ficaria em uma hospedagem diferente, com a requisção doscalculos sendo realizado por um servidor central, que buscaria os dados em outros servidores.

## Rotas para as operações
* Soma (https://calculadora-microservicos.vercel.app/api/soma) - Paulo Ricardo
* Subtração (https://calculadora-microservicos.vercel.app/api/subtracao) - Otavio Colimo
* Muliplicação (https://calculadora-microservicos.vercel.app/api/multiplicacao) Thiago Cunha 
* Divisão (https://calculadora-microservicos.vercel.app/api/divisao) - Vinicius de araujo
* [Aplicação Final](https://calculadora-microservicos-main.vercel.app)

## Executando o projeto
Para executar o projeto em sua máquina, siga os seguintes passos:

1. Clone o repositório
```
git clone https://github.com/seuusuario/calculadora-microservicos.git
```
2. Acesse a pasta do projeto
```
cd calculadora-microservicos
```
3. Instale as dependências
```
npm install
```
4. Execute o projeto
```
npm start
```

## Estrutura do projeto
A estrutura do projeto é a seguinte:
```
calculadora-microservicos
├── api
│   ├── divisao.js
│   ├── multiplicacao.js
│   ├── soma.js
│   └── subtracao.js
├── public
│   ├── css
│   │   └── style.css
│   └── js
│       └── script.js
├── views
│   ├── divisao.ejs
│   ├── index.ejs
│   ├── multiplicacao.ejs
│   ├── soma.ejs
│   └── subtracao.ejs
├── .gitignore
├── app.js
├── package.json
└── README.md
```

## Tecnologias utilizadas
* Node.js
* Express
* EJS
* Axios
* Cors

## Autores
* [Paulo Ricardo](https://github.com/pauloricardo)
* [Otavio Colimo](https://github.com/otaviocolimo)
* [Thiago Cunha](https://github.com/thiagocunha)
* [Vinicius de Araujo](https://github.com/viniciusdearaujo)

## Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato
Para mais informações, entre em contato pelo e-mail contato@calculadora-microservicos.com.br
