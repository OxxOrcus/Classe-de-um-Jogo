# Jogo de Aventura - Classe de Herói

Este projeto em JavaScript é uma simples implementação de um jogo de aventura, onde uma classe `Heroi` representa personagens com habilidades de ataque personalizadas com base em seu tipo (como guerreiro, mago, monge e ninja).

## 🎯 Objetivo

Criar uma classe genérica que represente um herói de aventura com as seguintes propriedades:

- **nome**: Nome do herói
- **idade**: Idade do herói
- **tipo**: Tipo do herói (ex: guerreiro, mago, monge, ninja)

Além disso, a classe inclui um método `atacar` que exibe uma mensagem customizada conforme o tipo de herói e sua habilidade de ataque.

## 🚀 Tecnologias Utilizadas

- JavaScript ES6+
- Node.js (opcional para rodar localmente)

## 📦 Estrutura do Projeto

- `heroi.js`: Arquivo principal contendo a implementação da classe `Heroi`.
- `index.js`: Arquivo de exemplo para instanciar e testar o funcionamento da classe `Heroi`.

## ⚙️ Funcionamento do Método `atacar`

O método `atacar` utiliza a propriedade `tipo` para determinar o ataque realizado:

- **Mago** -> "usou magia"
- **Guerreiro** -> "usou espada"
- **Monge** -> "usou artes marciais"
- **Ninja** -> "usou shuriken"

## 📄 Exemplo de Uso

```javascript
// Importa a classe Heroi (se aplicável)
const Heroi = require('./heroi');

// Instancia heróis com tipos diferentes
const heroi1 = new Heroi("Arthur", 30, "guerreiro");
const heroi2 = new Heroi("Merlin", 150, "mago");

// Executa o método atacar
heroi1.atacar();  // Saída esperada: O guerreiro atacou usando espada
heroi2.atacar();  // Saída esperada: O mago atacou usando magia
