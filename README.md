# Calculadora em Microserviços
Esta aplicação demonstra a arquitetura de microserviços através de uma calculadora web. O design implementa cada operação matemática (soma, subtração, multiplicação e divisão) como serviços independentes hospedados em endpoints distintos. Um servidor central coordena as interações, recebendo solicitações do usuário e direcionando-as para o microserviço apropriado conforme a operação escolhida. Essa abordagem modular permite desenvolvimento, implantação e escalabilidade independentes de cada componente funcional da calculadora.

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

