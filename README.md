# Cálculo de Partidas Rankeadas (JavaScript)

Este projeto foi desenvolvido durante o **Bootcamp do Santander 2024 - Criando Jogos com Godot**. O objetivo do projeto é criar um programa em **JavaScript** que calcula resultados de partidas rankeadas com base em diferentes critérios.

## Funcionalidades

- **Cálculo de Resultados**: O programa calcula o desempenho em partidas rankeadas, levando em consideração vitórias, derrotas e empates.
- **Interatividade**: Os usuários podem inserir dados e obter resultados instantâneos.

## Tecnologias Utilizadas

- **JavaScript**: Linguagem de programação utilizada para implementar a lógica de cálculo.
- **HTML/CSS**: Utilizados para a estruturação e estilização da interface do usuário.

## Instruções para Execução

### Executando o Código

A primeira tela do projeto mostra a execução do código JavaScript.

![Executando o código](https://github.com/luanalamonica/Calculadora-Partidas/blob/main/primeira%20tela.png?raw=true)

#### Código Exemplo em JavaScript

```javascript
// Exemplo de código para calcular partidas rankeadas
function calcularPartidas(vitorias, empates, derrotas) {
    const pontos = (vitorias * 3) + (empates * 1);
    return `Pontos totais: ${pontos}`;
}

// Exemplo de uso
const resultado = calcularPartidas(10, 5, 3);
console.log(resultado); // Saída: Pontos totais: 35
```

## Como Executar o Projeto

Clone este repositório:

```bash
git clone https://github.com/luanalamonica/Calculadora-Partidas.git
```

## Como Executar o Projeto

Abra o arquivo HTML em um navegador web para executar o código JavaScript e visualizar o cálculo das partidas rankeadas.

## Estrutura do Projeto

- **Scripts JavaScript**: Contém a lógica do programa para calcular as partidas rankeadas.
- **HTML/CSS**: Estrutura e estilo da interface do usuário.

## Melhorias Futuras

- Implementar mais funcionalidades, como gráficos de desempenho e análises estatísticas.
- Criar uma interface gráfica mais interativa para entrada de dados do usuário.
- Adicionar animações ou efeitos visuais para melhorar a experiência do usuário.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para adicionar novas funcionalidades, melhorar o código ou ajustar a interface. Para contribuir:

1. Faça um _fork_ deste repositório.
2. Crie uma _branch_ com a nova funcionalidade (`git checkout -b feature/nova-funcionalidade`).
3. Envie suas alterações para o repositório (`git push origin feature/nova-funcionalidade`).
4. Abra um _pull request_ para revisão.
