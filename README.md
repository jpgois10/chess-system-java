# ♟️ Sistema de Xadrez em Java  

Este é um projeto de um **jogo de xadrez** desenvolvido em **Java 21**, criado para ser jogado diretamente no terminal. Ele utiliza conceitos avançados de **Orientação a Objetos (OOP)** e implementa as principais funcionalidades do xadrez, tornando-o uma experiência desafiadora e completa.  

🛠️ **Este projeto foi desenvolvido como parte do curso de Java do Professor Nélio Alves - Udemy.**  

---

## 🚀 Funcionalidades  

✅ **Movimentação das Peças:** Todas as peças seguem as regras oficiais do xadrez.  
✅ **Promoção de Peões:** Quando um peão alcança a última linha do tabuleiro, ele pode ser promovido a uma peça mais poderosa (Rainha, Cavalo, Bispo ou Torre).  
✅ **Roque:** Suporte ao movimento especial de roque.  
✅ **Captura En Passant:** Implementação da captura especial de peões "en passant".  
✅ **Cheque e Cheque-Mate:** O jogo detecta automaticamente situações de cheque e cheque-mate.  
✅ **Controle de Peças Capturadas:** Registra todas as peças capturadas ao longo da partida.  
✅ **Destaque de Movimentos Possíveis:** O terminal exibe os movimentos válidos para a peça selecionada, facilitando a visualização.  

🎨 **Experiência Visual:**  
- Jogadores são diferenciados por cores no terminal:  
  - **WHITE** (peças brancas).  
  - **BLACK** (peças pretas, destacadas em amarelo).  
- As jogadas possíveis para uma peça são realçadas no terminal, auxiliando no planejamento estratégico.  

---

## 📂 Estrutura do Projeto  

- **application/**
  - Program.java: Classe principal que executa o jogo.
  - UI.java: Classe responsável pela interface do usuário no terminal.
    
- **boardgame/**
  - Board.java: Classe que representa o tabuleiro do jogo.
  - Piece.java: Classe que representa uma peça genérica no tabuleiro.
  - Position.java: Classe que representa uma posição no tabuleiro.
  - BoardException: Classe representando exceções relativas à movimentação no tabuleiro.
    
- **chess/**
  - ChessException.java: Classe que representa exceções específicas do xadrez.
  - ChessMatch.java: Classe que gerencia uma partida de xadrez.
  - ChessPiece.java: Classe abstrata que representa uma peça de xadrez.
  - ChessPosition.java: Classe que traduz posições de xadrez (e.g., a1, e5) para posições de tabuleiro.
  - Color.java: Enumeração que representa as cores das peças (PRETO e BRANCO).
 
- **chess/pieces/**
  - Bishop.java: Classe da peça Bispo.
  - King.java: Classe da peça Rei.
  - Knight.java: Classe da peça Cavalo.
  - Pawn.java: Classe da peça Peão.
  - Queen.java: Classe da peça Rainha.
  - Rook.java: Classe da peça Torre.
  
---

## 🔑 Peças e Representações  

As peças são representadas no terminal pelos seguintes símbolos:  
- **B:** Bispo  
- **K:** Rei  
- **N:** Cavalo  
- **P:** Peão  
- **Q:** Rainha  
- **R:** Torre  

---

## ▶️ Como Executar  

1. **Clone o repositório para sua máquina local:**  
   ```bash
   git clone https://github.com/jpgois10/chess-system-java.git

2. **Execute o jogo:**
   ```bash
   java application/Program
   
---
## 🎮 Como Jogar

1. **Inicie o Jogo:** Após executar o programa, o tabuleiro será exibido no terminal com as peças posicionadas.
  ```bash
    8 R N B Q K B N R
    7 P P P P P P P P
    6 - - - - - - - -
    5 - - - - - - - -
    4 - - - - - - - -
    3 - - - - - - - -
    2 P P P P P P P P
    1 R N B Q K B N R
      a b c d e f g h
      
    Captured pieces:
    White: []
    Black: []
      
    Turn: 1
    Waiting player: WHITE
      
    Source:
  ```
     
2. Informe a posição de origem ('Source') e a de destino ('Target') usando a letra da coluna e o número da linha.
  ```bash
    8 R N B Q K B N R
    7 P P P P P P P P
    6 - - - - - - - -
    5 - - - - - - - -
    4 - - - - - - - -
    3 - - - - - - - -
    2 P P P P P P P P
    1 R N B Q K B N R
      a b c d e f g h
    
    Target:
  ```

---

## 📝 Regras Gerais  

- O jogo segue as regras oficiais do xadrez.  
- Para promover um peão, insira a letra correspondente à peça desejada (**B**, **N**, **R**, **Q**).  
- O jogo termina automaticamente em situações de cheque-mate.  

---

## 🎓 Sobre o Projeto  

Este jogo foi desenvolvido para consolidar conceitos de **Orientação a Objetos (OOP)**, como:  
- Herança  
- Polimorfismo  
- Encapsulamento  
- Modularização  

O código é otimizado para manutenção e futuras expansões, seguindo boas práticas de programação.  

---

## 🌟 Contribua  

Contribuições são sempre bem-vindas! Se você tiver ideias ou sugestões, fique à vontade para abrir uma issue ou enviar um pull request.  

---

**✨ Divirta-se jogando e bons estudos!**  

---

## 📜 Licença

Este projeto está licenciado sob a licença [MIT](https://opensource.org/licenses/MIT).  
Você pode usar, modificar e distribuir o código livremente, respeitando os termos desta licença.


