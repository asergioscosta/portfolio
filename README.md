# Portfolio

### Índice

- [Descrição do Projeto](#descrição-do-projeto)

- [Requisitos](#requisitos)

- [Funcionalidades](#funcionalidades)

- [Técnicas e Tecnologias Utilizadas](#técnicas-e-tecnologias-utilizadas)

- [Acesso ao Projeto](#acesso-ao-projeto)

- [Abrir e Executar o Projeto](#abrir-e-executar-o-projeto)

- [Desenvolvedores](#desenvolvedores)


## Descrição do Projeto

Este projeto consiste no desenvolvimento de um portfólio pessoal como parte da matéria de Desenvolvimento de Web Site da Faculdade Metodista Granbery. O portfólio visa apresentar informações sobre minha formação acadêmica, atuação profissional, habilidades tecnológicas e projetos pessoais.

## Requisitos

1. **Criação das Classes Abstratas:**
   - As Classes `Conta` e `Pessoa` são classes abstratas, ou seja, objetos não podem ser instanciados a partir dessas classes.

2. **Criação da Interface `IUsuario`:**
   - A interface `IUsuario` possui apenas a assinatura de um método.
   - O método, quando implementado nas classes que realizam a interface, deve retornar apenas `True`.

3. **Criação das Classes Concretas:**
   - As classes concretas correspondem a todas as demais classes, sendo que algumas delas possuem relacionamento de herança com as classes abstratas do modelo.

Considerações sobre os Métodos nas Classes Concretas:

   a. **Método `listarEnderecos()` da classe `Cliente`:**
      - O método deve imprimir no console todos os endereços armazenados para um cliente.

   b. **Método `depositar()` da classe `Conta`:**
      - Cria um objeto do tipo `Credito` vinculado à conta que está recebendo o depósito.

   c. **Método `sacar()` da classe `Conta`:**
      - Cria um objeto do tipo `Debito` vinculado à conta que está sofrendo o saque.
      - A conta não pode ter saldo negativo além do seu limite.

   d. **Método `transferir()` da classe `ContaCorrente`:**
      - Retira dinheiro da conta corrente de origem e envia para uma conta destino.
      - A conta não pode ter saldo negativo além do seu limite.

   e. **Método `calcularSaldo()` da `ContaPoupanca`:**
      - Soma o valor de todos os créditos e subtrai pela soma dos valores de todos os débitos.

   f. **Método `calcularSaldo()` da `ContaCorrente`:**
      - Soma o valor de todos os créditos e subtrai pela soma dos valores de todos os débitos.
      - Após, soma o valor do limite.
      - Ao final, retorna o valor.

## Funcionalidades

1. **Menu:**
    - O portfólio deve conter um menu com links para as principais páginas.
    - O menu deve ser exibido em todas as páginas.
    
2. **Rodapé:**
    - O rodapé deve conter links para suas redes sociais (LinkedIn, Twitter, etc).
    - O rodapé deve ser exibido em todas as páginas.
    - Os links para as redes sociais devem ser abertos em uma nova aba do navegador.
    
3. **Página principal:**
    - O conteúdo deve ser elaborado pelo aluno.
    
4. **Sobre mim:**
    - O conteúdo deve ser elaborado pelo aluno.
    
5. **Formação:**
    - Página que apresenta sua formação acadêmica e complementar.
    
6. **Atuação profissional:**
    - Página que descreve sua atuação profissional.
    
7. **Contato:**
    - Página com informações de contato.
        - Contatos pessoais.
        - Links para redes sociais (mesmo já estando no rodapé).
        - Incluir formulário de contato por e-mail (Observação: o formulário não enviará e-mail, pois depende de back-end).
    
8. **Portfólio:**
    - Página que descreve os projetos que você já desenvolveu ou ao menos 5 projetos fictícios.
        - Sugestões de informações dos projetos: nome do projeto, descrição, imagem, link para o projeto, link para o repositório.
        - Apresentar as tecnologias utilizadas no desenvolvimento do projeto. Cada uma das tecnologias deve possuir um link que redireciona para a página descrita no item 9.
    
9. **Descrição tecnologia:**
    - Página que descreve determinada tecnologia.
        - Sugestões de informações: nome, site oficial, definição da tecnologia, 3 prós, 3 limitações e 6 grandes projetos que utilizam a tecnologia.
        - Exemplo: [HTML5 - Reviews, Pros & Cons | Companies using HTML5 (stackshare.io)](https://stackshare.io/html5/reviews)

## Técnicas e Tecnologias Utilizadas

- **Linguagem de Marcação:** ``HTML5``
- **Ambiente de Desenvolvimento:** ``Visual Studio Code``

## Acesso ao Projeto

Você pode acessar os arquivos do projeto [clicando aqui](https://github.com/asergioscosta/portfolio) ou [baixá-lo como um arquivo zip](https://github.com/asergioscosta/portfolio/archive/refs/heads/main.zip).

## Abrir e Executar o Projeto

Após baixar o projeto, siga as instruções abaixo para abrir e executá-lo utilizando o `Visual Studio Code`.

1. Abra o Visual Studio Code;
2. No menu principal, selecione "File" -> "Open Folder" e navegue até o diretório onde você baixou o projeto;
3. Selecione a pasta do projeto e clique em "Open";
4. Crie as aplicações do projeto e os códigos.

## Desenvolvedores

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/102989796?v=4" width=115>](https://github.com/asergioscosta)