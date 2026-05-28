# Flappybird

Um clone simples de Flappy Bird desenvolvido na Unity como projeto de estudo e aprendizado.

![Screenshot do jogo](screenshot.png)

---

## Sobre o jogo

Controle o pássaro, desvie dos canos e tente alcançar a maior pontuação possível.

A partida começa parada e só inicia quando o jogador pressiona uma tecla. Conforme a pontuação aumenta, a velocidade dos canos também aumenta, tornando o jogo progressivamente mais difícil.

---

## Funcionalidades

* Sistema de pontuação.
* Melhor pontuação (Best Score).
* Salvamento automático da melhor pontuação em arquivo JSON.
* Música de fundo em loop.
* Efeitos sonoros de pulo, pontuação e colisão.
* Reinício rápido da partida.
* Aumento gradual da dificuldade.
* Jogo leve e totalmente offline.

---

## Controles

| Tecla          | Ação              |
| -------------- | ----------------- |
| Espaço         | Pular             |
| Qualquer tecla | Iniciar partida   |
| R              | Reiniciar partida |
| Esc            | Fechar o jogo     |

---

## Melhor Pontuação

A melhor pontuação é salva automaticamente em um arquivo chamado:

```text
bestScore.json
```

No Windows, o arquivo geralmente fica em:

```text
C:\Users\SEU_USUARIO\AppData\LocalLow\DefaultCompany\Flappybird\bestScore.json
```

Exemplo:

```json
{
    "bestScore": 9
}
```

---

## Download

Baixe a versão mais recente na seção **Releases** deste repositório.

---

## Requisitos

* Windows 10 ou superior
* Teclado

---

## Informações

Versão atual: **1.0**

Engine utilizada: **Unity**

Status do projeto: **Concluído**

---

## Licença

Este projeto foi desenvolvido para fins de estudo e aprendizado.
