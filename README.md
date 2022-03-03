# Trybe Wallet

<div> 
  <a href="https://www.linkedin.com/in/eder-santos-dev/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href = "mailto:eder.mota@outlook.com"><img src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" target="_blank"></a> 
</div>

Esse projeto foi proposto pela Trybe para o desenvolvimento de uma aplicação Frontend CRUD (CREATE, READ, UPLOAD e DELETE) para utilização do React Redux como ferramenta de manipulação de estado. São utilizadas store Redux, reducers no Redux, actions no Redux, dispatchers no Redux, conecções Redux aos componentes React e actions assíncronas no Redux e em uma aplicação React. Para um bom funcionamento é necessário que cumpra os seguintes requisitos:
- Adicionar/remover/editar um gasto.
- Visualizar uma tabela com os gastos.
- Visualizar o gasto total convertido para uma moeda selecionada
- Criar página inicial com login com email, senha e botão
- Utilizar o Redux para salvar o estado global as informações
- Criar página da carteira
- Criar formulario com despesas e opção de adicionar despesa
- Implementar lógica para opções da moeda, com os valores: 'USD', 'CAD', 'EUR', 'GBP', 'ARS', 'BTC', 'LTC', 'JPY', 'CHF', 'AUD', 'CNY', 'ILS', 'ETH' e 'XRP'.
- Os pull requests com issues de linter não serão avaliados
- Inclusão de campos na tabela de gastos: Descrição, Tag, Método de pagamento, Valor, Moeda, Câmbio utilizado, Valor convertido, Moeda de conversão e Editar/Excluir

<!-- <img src="exemplo-image.png" alt="exemplo imagem"> -->

## 💵 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:
* você deve possuir o Visual Studio Code ou outro editor de código instalado

## 💴 Instalando Trybe Wallet

Para instalar o Trybe Wallet, siga estas etapas:

Linux:

* Faça o clone do projeto: 
`git clone git@github.com:edermotasantos/trybewallet.git`
* Entre na página através do comando:
`cd trybewallet`
* Caso não esteja na branch correta, mude para a branch desse projeto em específico:
`git checkout eder-mota-santos-project-trybewallet`
* Dentro da pasta instale as dependências:
`npm install`

## 💶 Usando Trybe Wallet

Para usar Trybe Wallet, siga estas etapas:
* Pode verificar se o projeto obedece as boas práticas com o linter ESLint digite os comandos `npm run lint`
* Dentro do seu diretório digite `npm start` para iniciar projeto no seu navegador
* Para testar todos os requisitos digite `npm test`
* Para testar somente um requisito digite `npm test nomedotest`, sendo "nomedotest" o nome do teste que deseja executar. Exemplo: para executar o teste "login", digite: `npm test login`
* Para rodar apenas um teste digite `.only` em describe. Ao invés de `describe(n-1 - ...)`, salve com `describe.only(n-1 - ...)`
* No navegador digite um e-mail no formato `alguem@alguem.com` e uma senha de 6 caracteres

Agora você já pode ver o funcionamento desse projeto!
