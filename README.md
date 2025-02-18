# Jogo da Forca

Este é um simples jogo da forca desenvolvido em Python. O objetivo do jogo é adivinhar uma palavra escolhida aleatoriamente antes de esgotar todas as chances.

## Como Jogar

1. O jogo exibe uma palavra oculta representada por "_".
2. O jogador deve tentar adivinhar a palavra digitando uma letra por vez.
3. Se a letra estiver na palavra, ela será revelada nas posições corretas.
4. Se a letra não estiver na palavra, o jogador perderá uma chance.
5. O jogador tem um total de 6 chances para acertar a palavra.
6. O jogo termina quando:
   - O jogador acerta todas as letras da palavra e vence.
   - O jogador esgota todas as chances e perde.

## Requisitos

- Python 3.x instalado na máquina.

## Como Executar

1. Clone este repositório ou baixe o arquivo.
2. Abra o terminal ou prompt de comando na pasta onde o arquivo está salvo.
3. Execute o seguinte comando:
   ```sh
   python forca.py
   ```

## Estrutura do Código

O jogo está estruturado da seguinte forma:
- **`limpar_tela()`**: Função para limpar o terminal antes de iniciar o jogo.
- **`game()`**: Função principal que executa toda a lógica do jogo.
- Escolha aleatória de palavras.
- Loop para capturar as tentativas do jogador.
- Verificação de acertos e erros.
- Exibição do resultado final.

## Exemplo de Execução
```
Bem-vindo(a) ao jogo da forca
Adivinhe a palavra abaixo:

_ _ _ _ _ _

Chances restantes: 6
Letras erradas:

Digite uma letra: a

_ a _ a _ a

Chances restantes: 6
Letras erradas:

Digite uma letra: x

_ a _ a _ a

Chances restantes: 5
Letras erradas: x
```

## Licença

Este projeto é de uso livre. Fique à vontade para modificar e compartilhar!

