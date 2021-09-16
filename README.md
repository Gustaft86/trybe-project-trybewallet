## Termos e acordos

Ao iniciar este projeto, eu concordei com as diretrizes do Código de Ética e Conduta e do Manual da Pessoa Estudante da Trybe.

---

## Aplicação web

Uma carteira de controle de gastos com conversor de moedas, ao utilizar essa aplicação um usuário deverá ser capaz de:
  - Adicionar, remover e editar um gasto;
  - Visualizar uma tabelas com seus gastos;
  - Visualizar o total de gastos convertidos para uma moeda de escolha;

---

## Habilidades adquiridas
Neste projeto, fui desafiado à:

  * Criar um store Redux em aplicações React
  * Criar reducers no Redux em aplicações React
  * Criar actions no Redux em aplicações React
  * Criar dispatchers no Redux em aplicações React
  * Conectar Redux aos componentes React
  * Criar actions assíncronas na sua aplicação React que faz uso de Redux.

---

## Como foi desenvolvido

Formato do estado global:

```
{
  user: {
    email: '',
  },
  wallet: {
    currencies: [],
    expenses: []
  }
}
```

Para garantir a qualidade do código, utilizei o linter ESLint. 
Para gerenciamento das requisições assíncronas, utililizei Redux-Thunk. 

---

## Documentação da API de Cotações de Moedas

Está aplicação irá consumir os dados da API do _awesomeapi API de Cotações_ para realizar a busca de câmbio de moedas. Para realizar essas buscas, foi utilizado o seguinte _endpoint_:

- https://economia.awesomeapi.com.br/json/all

O retorno desse endpoint será algo no formato:

```
{
   {
     "USD": {
       "code":"USD",
       "codein":"BRL",
       "name":"Dólar Comercial",
       "high":"5.6689",
       "low":"5.6071",
       "varBid":"-0.0166",
       "pctChange":"-0.29",
       "bid":"5.6173",
       "ask":"5.6183",
       "timestamp":"1601476370",
       "create_date":"2020-09-30 11:32:53"
       },
      ...
   }
}
```

Mais detalhes, veja a [documentação](https://docs.awesomeapi.com.br/api-de-moedas).

---

## Testes unitários

Elaborados pela equipe de especialistas da Trybe, para verificação do progresso dos requisitos.

---

## Lista de requisitos

### Página de Login
#### 1. Crie uma página inicial de login com os seguintes campos e características:
#### 2. Crie uma página para sua carteira com as seguintes características:
### Header
#### 3. Crie um header para a página de carteira contendo as seguintes características:
#### 4. Desenvolva um formulário para adicionar uma despesa contendo as seguintes características:
#### 5. Desenvolva uma tabela com os gastos contendo as seguintes características:
#### 6. Crie um botão para deletar uma despesa da tabela contendo as seguintes características:
### Bônus
#### 7. Crie um botão para editar uma despesa da tabela contendo as seguintes características:

