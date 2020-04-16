## Projeto Consumidor

É um portal onde se pode consultar dados de Consumidores atraves do CPF.

Um ponto importante é que todos os dados que constam cadastrados nos bancos de dados do projeto, são claramente fictícios.

## Sobre

O portal foi construido usando a arquitetura de <b>micros serviços</b>, onde a estrutura do projeto é dividida em uma <b>aplicação front-end</b> e <b>API's em back-end</b>;

* **Back-end**: 
<b>servicesConsumidor</b>
Dividido em três serviços, onde cada um é executado pelo seu container.

* **Front-end**: 
<b>app-consumidor</b>
Um portal onde é necessário fazer um login para poder fazer a consulta do CPF.

## Pré Requisitos
Para executar o projeto, será necessário que tenha instalado na sua máquina os seguintes programas:
* Docker
* Docker Compose
* NPM

## Criado e mantido por

- **Lucas Vieira (lucsolivier@gmail.com)**