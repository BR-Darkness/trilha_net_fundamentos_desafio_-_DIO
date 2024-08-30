<h1 align="center">
    <a href="https://www.dio.me/">
        <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png">
    </a>
    <span> DIO - Trilha .NET - Fundamentos</span>
</h1>

<br>

> [!NOTE]  
> Desafio proposto pela [Digital Innovation One](www.dio.me)

<br>

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de fundamentos, da trilha .NET da DIO.

<br>

## Contexto

<p align="justify">Você foi contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.</p>

<br>

## Proposta
Você precisará construir uma classe chamada "Estacionamento", conforme o diagrama abaixo:

<br>
<p align="center"><img alt="Diagrama de classe estacionamento" src="diagrama_classe_estacionamento.png"></p>
<p align="center"><small>Diagrama de classe estacionamento</small></p>
<br>

### A classe contém três variáveis, sendo:

- **precoInicial**: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

- **precoPorHora**: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

- **veiculos**: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

<br>

### A classe contém três métodos, sendo:

- **AdicionarVeiculo**: Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.

- **RemoverVeiculo**: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** * **precoPorHora**, exibindo para o usuário.

- **ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

<br>

### Por último, deverá ser feito um menu interativo com as seguintes ações implementadas:

1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

<br>

## Solução
<blockquote align="justify">O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.</blockquote>
