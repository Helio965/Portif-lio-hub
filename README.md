git init
git add .
git commit -m "Versão inicial do jogo de cartas"
git remote add origin https://github.com/seuusuario/jogo-de-cartas.git
git push -u origin master

# Jogo de Cartas

Este é um jogo simples de tirar cartas aleatórias de um baralho, feito com HTML, CSS e JavaScript.

## Como Funciona

- Ao clicar no botão "Tirar Carta", uma carta aleatória do baralho será exibida na tela.
- O baralho contém 52 cartas, divididas em 4 naipes: Espadas, Copas, Ouros e Paus.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript

## Como Jogar

1. Clone o repositório:
   ```bash
   // Baralho de cartas

// Função para tirar uma carta aleatória
function tirarCarta() {
    const cartaAleatoria = cartas[Math.floor(Math.random() * cartas.length)];
    document.getElementById("carta").innerHTML = `Você tirou: <strong>${cartaAleatoria}</strong>`;
}



---

### 5. **Adicionar e Enviar o README.md**

1. **Adicionar o README.md ao controle de versão:**

   ```bash
   git add README.md

git commit -m "Adicionado README.md com a documentação do projeto"
git push
