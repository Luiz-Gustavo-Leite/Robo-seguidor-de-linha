# 🤖 Robô Seguidor de Linha — Arduino UNO

Projeto Interdisciplinar desenvolvido no **6º Congresso de Projetos Interdisciplinares do Centro Universitário FAM**.

![Robô Seguidor de Linha](Robo%20seguidor%20de%20linha.png)

---

## 👥 Autor
- Luiz Gustavo Leite Soares  
---

## 📋 Descrição

Robô autônomo capaz de seguir uma linha preta sobre fundo branco, percorrendo um trajeto determinado (incluindo curvas) no menor tempo possível, sem intervenção humana.

---

## 🔧 Componentes Utilizados

| Material | Quantidade | Finalidade |
|---|---|---|
| Módulo infravermelho | 2 | Leitura da linha |
| Ponte H L298N | 1 | Controle dos motores |
| Arduino UNO | 1 | Microcontrolador |
| Bateria 9V | 1 | Alimentação |
| Motor TT DC 3-6V | 2 | Movimentação |
| Rodas 50mm | 2 | Movimentação |
| Chassi acrílico | 1 | Estrutura base |

**Dimensões:** 21 cm × 15 cm × 7 cm | **Peso:** 413,84 g

---

## 🧠 Lógica de Navegação

| Sensor 1 | Sensor 2 | Ação |
|---|---|---|
| Branco (0) | Branco (0) | Avança em linha reta |
| Preto (1) | Branco (0) | Vira para a esquerda |
| Branco (0) | Preto (1) | Vira para a direita |

---

## 🛠️ Como usar

1. Abra o arquivo `robo_seguidor.ino` na **Arduino IDE**
2. Conecte o Arduino UNO ao computador via USB
3. Selecione a placa e porta correta em **Ferramentas**
4. Clique em **Upload**
5. Posicione o robô na pista e ligue!

---

`Arduino` · `Robótica` · `Seguidor de Linha` · `C++` · `FAM`
