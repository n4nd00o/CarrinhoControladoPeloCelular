# 🤖 Carrinho Controlado pelo Celular

Projeto acadêmico desenvolvido durante a graduação em Engenharia de Software com o objetivo de aplicar conceitos de programação, eletrônica e robótica utilizando Arduino.

O sistema permite controlar um carrinho robótico através de um aplicativo móvel conectado via Bluetooth.

---

# Objetivo

Aplicar na prática os conhecimentos adquiridos em disciplinas relacionadas à programação, eletrônica e sistemas embarcados, desenvolvendo um robô controlado remotamente.

---

# Funcionalidades

- Controle do carrinho via Bluetooth
- Comunicação Serial entre Arduino e aplicativo móvel
- Controle independente de dois motores DC
- Movimentação para frente e para trás
- Controle de direção (esquerda e direita)
- Indicação visual do estado da conexão através de LED
- Controle de velocidade utilizando PWM

---

# Tecnologias utilizadas

- Arduino
- C++
- Comunicação Serial
- Bluetooth
- PWM
- Motores DC
- Ponte H
- Sistemas Embarcados

---

# Hardware utilizado

- Arduino Uno
- Módulo Bluetooth HC-05/HC-06
- Ponte H (L298N ou equivalente)
- Motores DC
- Protoboard
- LED indicador
- Fonte de alimentação

---

# Funcionamento

O aplicativo envia continuamente informações contendo:

- Estado do botão
- Coordenada X do joystick
- Coordenada Y do joystick

O Arduino interpreta esses dados através da comunicação serial e calcula:

- Direção do movimento
- Velocidade dos motores
- Sentido de rotação
- Estado da conexão Bluetooth

Caso a comunicação seja perdida por mais de 500 ms, o LED indicador é desligado.

---

# Estrutura do projeto

```
CarrinhoControladoPeloCelular/
│
├── carrinho.cpp
└── README.md
```

---

# Conceitos praticados

Durante este projeto foram estudados e aplicados conceitos como:

- Programação em C++
- Estruturas condicionais
- Comunicação Serial
- Comunicação Bluetooth
- Controle PWM
- Manipulação de pinos digitais e analógicos
- Controle de motores
- Sistemas embarcados
- Integração entre hardware e software

---

# O que aprendi

Este projeto contribuiu para meu entendimento sobre comunicação entre dispositivos, controle de atuadores e desenvolvimento para plataformas embarcadas.

Também permitiu compreender como integrar componentes eletrônicos e software para construir uma solução funcional.

---

# Melhorias futuras

Possíveis evoluções deste projeto incluem:

- Controle por Wi-Fi (ESP32)
- Sensores ultrassônicos para evitar obstáculos
- Câmera embarcada
- Controle por aplicativo próprio
- Telemetria em tempo real
- Controle de velocidade mais preciso
- Modo autônomo

---

# Observações

Projeto desenvolvido para fins acadêmicos durante a graduação em Engenharia de Software.

Seu objetivo principal foi colocar em prática conceitos de programação, eletrônica e robótica estudados em sala de aula.

---

# Licença

Projeto disponibilizado apenas para fins educacionais.
