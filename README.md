# Desafio multidisciplinar qwst

Bem-vindo ao desafio multidisciplinar da QWST! Este desafio foi projetado para avaliar suas habilidades em 3 áreas de conhecimento: Desenvolvimento WEB (HTML/CSS/JavaScript), SQL e Python.

Siga atentamente as instruções de cada questão, desenvolvendo o código necessário conforme solicitado.

Cada área de conhecimento possui seu respectivo repositório para os arquivos. Leia atentamente todas as instruções e certifique-se de seguir cada etapa conforme descrito.

## Regras

- Os desafios não possuem ordem fixa, podem ser feitos da forma que você preferir.
- Não pode usar AI (ChatGPT, Copilot, etc.). No entanto, você pode pesquisar na internet para buscar dicas ou ajudas e tirar dúvidas, mas não vale copiar soluções inteiras prontas.
- Cada script deve ser organizado e salvo na pasta correspondente à disciplina.
- Você tem 3 horas para finalizar o desafio. Gerencie o seu tempo adequadamente!

## Dicas

- **Planeje antes de codar:** Leia todas as instruções cuidadosamente e planeje como você vai estruturar seu código.
- **Teste frequentemente:** Teste cada funcionalidade à medida que você a desenvolve para garantir que tudo esteja funcionando corretamente.
- **Comente seu código:** Adicione comentários ao seu código para explicar o que cada parte faz. Isso ajudará na manutenção e na compreensão do código.
- **Utilize boas práticas:** Siga as boas práticas de desenvolvimento, como manter o código limpo e organizado, e utilizar nomes de variáveis e funções descritivos.
- **Gerenciamento de tempo:** Divida seu tempo de forma eficiente para garantir que você consiga completar todos os desafios dentro do prazo.

## Infraestrutura
Para realizar este desafio, você tem os seguintes softwares disponíveis. Utilize aqueles com os quais você se sinta mais confortável:

- Editores de Código:
   - Visual Studio Code (Vscode)
   - Sublime Text
   - Notepad++
   - Pycharm

- Linguagens e Bancos de Dados:
   - Python 3.10
   - SQL Server
   - PostgreSQL (Postgree)
   - MySQL
---

## 1. Desenvolvimento web (HTML/CSS/JavaScript)

Bem-vindo à primeira etapa do desafio multidisciplinar! Nesta fase, você será avaliado em suas habilidades de desenvolvimento web, utilizando HTML, CSS e JavaScript.

O objetivo é criar uma página web interativa que inclua um formulário, uma tabela para exibir os dados submetidos e funcionalidades adicionais para melhorar a experiência do usuário.

Você deve criar uma página HTML5 que contenha um formulário simples, estilizar a página com CSS e adicionar funcionalidades dinâmicas com JavaScript.

### HTML

1. **Formulário Básico**  
   Crie uma página HTML5 e inclua um formulário simples que contenha os seguintes campos:

   - "Nome"
   - "Email"
   - "Data de nascimento"
   - "Senha"

   Adicione um botão de envio para submeter o formulário.

2. **Inicialização da tabela**  
   Em outra seção da mesma página HTML:
   - Crie uma tabela vazia com as colunas correspondentes aos campos do formulário anterior.

### CSS

1. **Estilização de Botão com Hover e Clique**  
   Personalize a tabela e o botão de envio com CSS. O botão deve ter o seguinte comportamento:

   - Fundo azul e texto branco.
   - Quando o usuário passa o mouse sobre o botão, ele aumenta 10% de tamanho e o fundo muda para verde.

2. **Alinhamento**  
   Utilize CSS para garantir que, ao visualizar a página em um dispositivo móvel, o formulário seja exibido acima da tabela. Em telas maiores (Full HD ou superior), exiba o formulário e a tabela lado a lado.

3. **Estilo com framework**  
   Utilize um framework CSS de sua preferência para estilizar a página de forma consistente e visualmente agradável. Pode ficar a vontade para dar um toque seu à pagina.

### JavaScript

1. **Preenchimento dinâmico da tabela**

   - Preencha os dados da tabela com JavaScript após o envio do formulário.
   - Adicione uma coluna extra chamada "Idade".
   - A data na tabela deve ter o formato dd/mm/aaaa

2. **Verificação de Ano Bissexto**  
   Crie uma função em JavaScript que, após o preenchimento do formulário, exiba um alerta informando se o ano de nascimento da pessoa é bissexto.

3. **Cálculo de Idade**  
   Desenvolva um código JavaScript que calcule a idade da pessoa com base na data de nascimento fornecida no formulário e exiba essa idade na tabela.

4. **Mudança de Cor Aleatória no Background**  
   Adicione um botão no HTML que, ao ser clicado, altere a cor de fundo da página para uma cor aleatória. Utilize JavaScript para implementar a função que gera cores aleatórias (sinta-se à vontade para definir quais e quantas cores devem ser alternadas).

## 2. SQL

Bem-vindo à segunda etapa do desafio multidisciplinar! Nesta fase, você será avaliado em suas habilidades de SQL. O objetivo é criar consultas que manipulem e consultem dados em um banco de dados. Você pode utilizar qualquer um dos três bancos de dados instalados no seu PC: SQL Server, MySQL ou PostgreSQL.

As tabelas `Funcionarios` e `Clientes` já estão populadas nos respectivos bancos.

Você deve criar arquivos SQL que contenham as consultas para cada um dos desafios descritos abaixo. Os arquivos devem ser colocados dentro da pasta `SQL` e precisam funcionar corretamente no banco de dados escolhido.

1. **Listagem de Funcionários Recentes**  
   Utilizando a tabela `Funcionarios` Escreva uma query para listar os 5 funcionários mais novos, baseado na Data de Admissão.

2. **Criação de tabela**

   - Crie uma tabela `Vendas` com colunas `ID` (esta coluna deve ser unica e populada automaticamente), `ProdutoID` (não pode ser nulo), `Quantidade`,`Valor total da venda` e `Data da venda`.
   - Popule essa tabela com pelo menos 3 registros.
   - Exiba qual é a venda mais antiga
   - Exiba qual é a venda com o valor mais baixo
   - Apague as vendas que tenham data anterior a D-30

3. **Alteração de tabela**  
   - Inclua a coluna Vendedor na tabela Vendas do exercício anterior. 
   - Atualize a venda mais recente preenchendo o seu nome no campo do Vendedor.

4. **Contagem de Clientes por Cidade**  
   Dada a tabela `Clientes`, escreva uma query para contar quantos clientes existem em cada cidade, ordenando o resultado pela quantidade de clientes em ordem decrescente.

5. **Funcionários com Salário Acima da Média**  
   Crie uma query que exiba os nomes dos funcionários que ganham mais do que a média de salário de todos os funcionários na tabela `Funcionarios`.

## 3. Python

Bem-vindo à última etapa do desafio multidisciplinar! Nesta fase, você será avaliado em suas habilidades de programação em Python. O objetivo é criar funções que resolvam problemas específicos, utilizando boas práticas de programação.

Caso seja necessário utilizar alguma biblioteca externa, crie e use um ambiente virtual (venv).

Cada script deve ser colocado em um arquivo separado. Os arquivos devem ser colocados dentro da pasta `Python` e precisam funcionar corretamente.

1. **Função para Verificação de Número Primo**  
   Escreva uma função que receba um número inteiro positivo e retorne `True` se ele for um número primo e `False` caso contrário. Não utilize bibliotecas externas.

2. **Filtragem de Números Pares**  
   Escreva uma função que receba uma lista de números inteiros e retorne um dicionário contendo apenas os números pares da lista original. a Key do dicionário pode ser o índice da lista.

3. **Maior e Menor Número na Lista**  
   Crie uma função que receba uma lista de números e retorne o maior e o menor número da lista (sem usar as funções `max()` e `min()`).

4. **Feriados**
   Crie uma função que receba um ano como parâmetro e retorne um dataframe contendo todos os dias desse ano.
   O dataframe deve incluir as seguintes informações para cada dia:
   - A data
   - O dia da semana (Domingo a Sábado)
   - O nome do feriado, caso seja um feriado (caso contrário, deixe em branco)

Boa sorte!
