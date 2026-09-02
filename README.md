# 🌡️ SmartClass IoT — Control Center

> **Sistema de Monitoramento e Automação de Conforto Térmico para Ambientes Escolares**

 O **SmartClass IoT** é uma solução desenvolvida para monitorar em tempo real as condições térmicas e de umidade em salas de aula. Através do uso de microcontroladores e sensores, o sistema sinaliza visual e sonoramente a necessidade de intervenções no ambiente (como ligar ventiladores ou abrir janelas), garantindo um clima ideal para a concentração e o aprendizado.

---

## 👥 Integrantes do Projeto

* **Ana Clara Melo**
* **Gabriela do Nascimento**
* **Moana Astromecas**  
* **Turma:** 3B

---

## ⚙️ Funcionalidades do Dashboard

- 🔴 **Monitoramento em Tempo Real:** Leitura dinâmica de Temperatura (°C) e Umidade (%).
- 📊 **Telemetria e Status:** Classificação automática do estado da sala (`CONFORTÁVEL`, `ATENÇÃO`, `CRÍTICO`).
- 💡 **Feedback Visual dos Atuadores:** Sinalização na tela indicando qual LED do protótipo físico está ativo.
- ⚡ **Barra Dinâmica de Conforto:** Gradiente visual comparativo da faixa ideal de temperatura.
- 💻 **Código C++ Integrado:** Exibição do código embarcado utilizado no microcontrolador.

---

## 🛠️ Arquitetura de Hardware

| Componente | Função | Conexão / Pino |
| :--- | :--- | :--- |
| **Arduino UNO** | Processamento lógico do sistema | USB / Serial |
| **Sensor DHT11** | Captura de Temperatura e Umidade | Pino Digital 2 |
| **LED Amarelo** | Sinalização de Alerta/Atenção ($\ge 25^\circ\text{C}$) | Pino Digital 8 |
| **LED Vermelho + Buzzer** | Alerta Crítico Sonoro/Visual ($\ge 28^\circ\text{C}$) | Pinos Digitais 9 e 10 |

---

## 🚀 Como Executar o Projeto Localmente

1. Clone este repositório para o seu computador:
   ```bash
   git clone [https://github.com/gabrielapsdn/S.A-Joana---Gabi-e-Mo.git](https://github.com/gabrielapsdn/S.A-Joana---Gabi-e-Mo.git)
