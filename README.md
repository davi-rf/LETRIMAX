# **LETRIMAX**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![TXT](https://img.shields.io/badge/TXT-0A1A2F?style=for-the-badge&logo=readthedocs&logoColor=white)

**LETRIMAX** é um jogo de adivinhação de palavras inspirado no famoso jogo **Wordle**.

## 📝 Descrição

O objetivo do jogo é descobrir a **palavra secreta de 5 letras** em até **6 tentativas**. A cada tentativa, o jogo mostra quais letras estão corretas e em qual posição, utilizando cores para facilitar a visualização:

- 🟩 **Verde**: letra correta na posição correta  
- 🟨 **Amarelo**: letra correta na posição errada  
- ⬜ **Sem cor**: letra não está na palavra

## 🎮 Como jogar

1. Execute o arquivo `main.py`  
2. Escolha a velocidade de digitação  
3. Digite palavras de 5 letras válidas até acertar ou acabar as tentativas  
4. Veja seu placar ao final de cada rodada  

## ⚙️ Requisitos

- Python instalado  
- Biblioteca `unidecode`  
- Certifique-se de que o arquivo `br-utf8.txt` está na mesma pasta que o `main.py` (lamento a falta de palavras, estou buscando outra forma de inserir as palavras no jogo. Caso tenha alguma sugestão, por favor me ajude, **deixe uma issue**)

## Referência

FEOFILOFF, Paulo. *br-utf8.txt – Lista de palavras do português brasileiro*. São Paulo: Instituto de Matemática e Estatística da Universidade de São Paulo, 2025. [Disponível aqui](https://www.ime.usp.br/~pf/dicios). Acesso em: 09 ago. 2025.