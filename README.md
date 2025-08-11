# 🎵 Projeto Arduino: Megalovania

Este projeto reproduz a música **Megalovania** utilizando um Arduino e um buzzer piezoelétrico. O código foi adaptado para tocar a melodia completa quando um botão é pressionado.

---

## 🎶 Sobre a música

**Megalovania** é uma música composta por **Toby Fox**, originalmente para o jogo *Undertale* (2015). Ela é tocada durante a batalha contra o personagem **Sans**, sendo uma das trilhas mais icônicas da cultura gamer.

🔗 Ouça no Spotify: [Megalovania - Toby Fox](https://open.spotify.com/track/2TpxZ7JUBn3uw46aR7qd6V)

---

## 🧰 Materiais necessários

- 1x Placa Arduino (Uno, Nano, etc.)
- 1x Buzzer piezoelétrico
- 1x Botão push-button
- 1x Resistor de 10kΩ (para o botão)
- Jumpers e protoboard

---

## ⚙️ Esquema de ligação

- **Buzzer**: pino positivo no **pino 10** do Arduino, negativo no GND
- **Botão**: um lado no **pino 8**, outro no GND com resistor de pull-down

---

## 📂 Arquivo

O código está no arquivo `Megalovania.ino`. Ele define as frequências das notas musicais e a sequência da melodia. Quando o botão é pressionado, a música começa a tocar.

---

## 🧠 Como funciona

- O código usa a função `tone()` para gerar sons no buzzer.
- As notas são definidas com `#define` no início do código.
- A melodia é executada dentro do `loop()` quando o botão é pressionado.

---

## 🚀 Como usar

1. Abra o arquivo `Megalovania.ino` na IDE do Arduino.
2. Conecte os componentes conforme o esquema.
3. Faça o upload do código para a placa.
4. Pressione o botão para ouvir a música!

---

## 📌 Observações

- O buzzer deve ser do tipo **ativo** ou **passivo** (preferencialmente passivo para melhor controle de notas).
- O tempo de execução da música é longo, pois a melodia é completa.
- O código pode ser adaptado para usar interrupções ou outros gatilhos.

---

## 📜 Licença

Este projeto é de uso livre para fins educacionais e não comerciais. Créditos da música para Toby Fox.
