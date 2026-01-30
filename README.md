<div align="center">
  <h1>LETRIMAX</h1>

  <img src='https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54'>
  <img src='https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white'>
  <img src='https://img.shields.io/badge/License-MIT-green?style=for-the-badge'>
</div>

<p align="right">Jogo de adivinhação de palavras inspirado no famoso jogo <b>Wordle</b> feito em <b>Python</b>.</p>

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

---

## Referência

FEOFILOFF, Paulo. _br-utf8.txt – Lista de palavras do português brasileiro_. São Paulo: Instituto de Matemática e Estatística da Universidade de São Paulo, 2025. [Disponível aqui](https://www.ime.usp.br/~pf/dicios). Acesso em: 09 ago. 2025.

## Licença

Este projeto está sob a licença **MIT**.
