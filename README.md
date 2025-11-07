# 🚗 Mini Jogo de Controle de Carros

## 📋 Sobre o Projeto

Um jogo interativo onde você pode selecionar e controlar carros em uma pista animada. Desenvolvido para demonstrar manipulação avançada de DOM, eventos e animações com CSS e JavaScript.

## 🎮 Funcionalidades

### 🚘 Seleção de Carros
- **Carro Branco** (White Lotus)
- **Carro Vermelho** (Red Jaguar)
- Seleção por clique nos carros ou nos botões circulares

### 🎯 Controles
- **Acelerar**: Movimenta o carro para frente
- **Desacelerar**: Retorna o carro para trás
- **Resetar**: Volta ao estado inicial
- **Controle por Teclado**: Setas ↑ (acelerar) e ↓ (desacelerar)

### ✨ Efeitos Visuais
- **Mudança de Background**: Cor do fundo muda conforme o carro selecionado
- **Efeito de Perspectiva**: Carro diminui e sobe ao acelerar (ilusão 3D)
- **Movimento Lateral**: Deslocamento realista na pista
- **Pista Animada**: Background com efeito de movimento

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Animações, transições e efeitos visuais
- **JavaScript** - Lógica do jogo e manipulação DOM

## 📁 Estrutura do Projeto

```
carro-jogo/
├── index.html
├── style.css
├── script.js
└── assets/
    ├── img/
    │   ├── track.gif
    │   ├── white_lotus.png
    │   └── red_jaguar.png
    └── audio/
        └── cars.mp3
```

## 🎨 Design e Interface

### Elementos Visuais:
- **Pista Animada**: GIF com efeito de movimento
- **Carros Estilizados**: Imagens PNG de alta qualidade
- **Botões Intuitivos**: Design circular para seleção
- **Feedback Visual**: Mudanças de cor e posição

### Layout:
- **Header**: Informações do carro selecionado
- **Main**: Área da pista com os carros
- **Footer**: Controles de navegação

## ⚙️ Mecânicas do Jogo

### Sistema de Seleção:
```javascript
// Exemplo da função de seleção
function selecionarCarro(carro, outroCarro, cor, nome) {
    // Atualiza interface
    // Aplica efeitos visuais
    // Habilita controles
}
```

### Sistema de Movimento:
- **Posição**: Controlada por variável (0-100)
- **Aceleração**: +10 unidades por clique
- **Desaceleração**: -10 unidades por clique
- **Limites**: Mínimo 0, máximo 100

### Efeitos de Perspectiva:
- **Tamanho**: Diminui 0.2px por unidade
- **Altura**: Sobe 0.4px por unidade  
- **Movimento Lateral**: 0.8px por unidade

## 🎵 Elementos Multimídia

- **Áudio de Fundo**: Trilha sonora ambiente (cars.mp3)
- **Imagens Otimizadas**: Carros e pista em PNG/GIF
- **Ícone Personalizado**: Emoji de carro no favicon

## 📱 Responsividade

- Layout centralizado
- Controles fixos no footer
- Compatível com dispositivos móveis
- Interface adaptável

## 🎯 Objetivos do Projeto

- Praticar manipulação avançada de DOM
- Implementar sistema de controles múltiplos
- Criar efeitos visuais com CSS e JavaScript
- Desenvolver interface interativa e intuitiva
- Trabalhar com eventos de teclado e mouse

## 🕹️ Como Jogar

1. **Selecione um carro** clicando nele ou no botão circular
2. **Use os controles** para acelerar/desacelerar
3. **Experimente as setas** ↑↓ do teclado
4. **Reset** para começar novamente

## 🌐 Demo

O projeto está disponível para teste:
[**Jogar Mini Jogo de Carros**](https://gabryelpaivadev.github.io/Mini-Jogo-da-Carro/)

---

**Desenvolvido por Gabryel Paiva** 🚀
