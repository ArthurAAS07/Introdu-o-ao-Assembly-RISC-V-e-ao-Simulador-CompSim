# Introdu-o-ao-Assembly-RISC-V-e-ao-Simulador-CompSim
Códigos das atividades do Laboratório 2 sobre Introdução ao Assembly RISC-V e ao Simulador CompSim.

---

## ⚙️ Atividades

### 🔹 Atividade 1 — Codificação de pseudo-código

Implementa um pseudo-código que:

- Carrega três valores (`a`,`b` e `m`)
- Se `b >= a`, mantém `a`
- Caso contrário, soma `a + b`
- Armazena o resultado em `m`

---

### 🔹 Atividade 2 — Codificação de pseudo-código

Implementa um código onde:

- Se `b < m`, realiza soma (`a + b`)
- Caso contrário, realiza subtração (`a - b`)
- Resultado é salvo em `m`

---

### 🔹 Atividade 3 — Tradução de fluxograma

Simula um fluxograma com decisão:

- Se `i == j`, executa soma (`g + h`)
- Caso contrário, executa subtração (`g - h`)
- Resultado é armazenado em `f`

---

### 🔹 Atividade 4 — Print "Hello World"

Imprime a string `"Hello World"` na saída do simulador.

- Percorre a string byte a byte
- Envia cada caractere para o endereço de saída (`1024`)

---

### 🔹 Atividade 5 — Echo até caractere '*'

Lê caracteres da entrada e imprime na saída até que o usuário digite `'*'`.

- Entrada: endereço `1025`
- Saída: endereço `1024`
- Para quando detecta ASCII `42`

---

### 🔹 Atividade 6 — Controle de LEDs (Simulação Arduino)

Simula um efeito de LEDs acendendo sequencialmente.

- Inicia com o primeiro LED ligado
- A cada entrada, desloca para o próximo LED
- Para ao atingir o limite

- Entrada: `1026`
- Saída: `1029`

---
