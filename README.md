# Arduino Servo Control

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform: Arduino](https://img.shields.io/badge/Platform-Arduino-00979D.svg)](https://www.arduino.cc/)
[![Language: C++](https://img.shields.io/badge/Language-C++-f34b7d.svg)](https://isocpp.org/)

Controle de servomotores utilizando microcontroladores Arduino e a biblioteca padrão `<Servo.h>`. Desenvolvido como material de suporte e soluções práticas para automação e controle de posição angular.

---

## 📌 Visão Geral

O projeto aborda o posicionamento preciso de servomotores (como o micro servo SG90 / MG90S) através de sinais PWM (Pulse Width Modulation), cobrindo:
- Varredura angular contínua de 0° a 180° e retorno suave.
- Controle por passos com temporização configurável.
- Resolução dos exercícios das aulas práticas de microcontroladores (Aula Prática 6).

---

## 🔌 Hardware e Conexões

| Pino do Servomotor | Função | Conexão Arduino |
| :--- | :--- | :--- |
| **Marrom / Preto** | GND (Terra) | `GND` |
| **Vermelho** | VCC (+5V) | `5V` (ou fonte externa 5V com terras comuns) |
| **Laranja / Amarelo**| Sinal PWM | Pino Digital `9` ou `10` |

> ⚠️ **Nota:** Para projetos com múltiplos servomotores ou cargas maiores, utilize uma fonte de alimentação externa de 5V para evitar sobrecarga no regulador do Arduino.

---

## 📁 Estrutura do Repositório

```text
Arduino-Servo-Control/
├── images/             # Diagramas e esquemáticos de ligação
├── src/
│   ├── Aula_Pratica_6_Q1/   # Questão 1: Controle básico e varredura
│   └── Aula_Pratica_6_Q2/   # Questão 2: Movimentação incremental com temporização
└── README.md
```

---

## 🚀 Como Executar

1. Abra a [Arduino IDE](https://www.arduino.cc/en/software).
2. Conecte sua placa Arduino à porta USB.
3. Abra um dos arquivos `.ino` na pasta `src/`.
4. Selecione a placa correspondente (ex: *Arduino Uno*) e a porta serial em **Ferramentas > Porta**.
5. Clique em **Carregar (Upload)**.

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).
