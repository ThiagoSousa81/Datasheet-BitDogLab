<h1 align=center>Datasheet BitDogLab</h1>
Descrição de fácil acesso dos pinos da BitDogLab

> OBS.: Essa descrição de pinos é da placa BitDogLab v6.3 do programa TIC-37 EmbarcaTech.
>
> Lembre-se de consultar o datasheet do Raspberry Pi Pico W se discordar de algo aqui

<h2 align=center>Se isso lhe ajudou de alguma forma, deixe-me uma ⭐ neste repo</h2>
<h3 align=center> 
  
  ![DatasheetPicoW](https://github.com/ThiagoSousa81/Test-Pooling/blob/main/2_BDL_RGB.jpg)
  
</h3>

<details><summary><h2>Portas do barramento I2C</h2></summary>

> Ainda não fiz um teste, mas deduzindo o [código](https://github.com/wiltonlacerda/EmbarcaTechU4C1/blob/0d970b14796fd2ac0be7dea3b164f76429509696/ArquivosUF2/DeFabrica/BitDogLab_Original.py#L9) que veio de fábrica seria assim...

| Componente | Pino |
| --- | --- |
| I2C 0 (SDA) | 14 |
| I2C 0 (SCL) | 15 |
| I2C 1 (SDA) | 16 |
| I2C 1 (SCL) | 17 |

</details>

<details><summary><h2>Microfone</h2></summary>

| Componente | Pino |
| --- | --- |
| Microfone | GPIO 28 |

</details>

<details><summary><h2>Display OLED</h2></summary>

| Componente | Pino |
| --- | --- |
| OLED (SCL) | 15 |
| OLED (SDA) | 14 |

</details>

<details><summary><h2>Joystick</h2></summary>

| Componente | Pino |
| --- | --- |
| VRx (Joystick) | GPIO 26 |
| VRy (Joystick) | GPIO 27 |
| Botão Joystick | GPIO 22 |

</details>

<details><summary><h2>Matriz de LEDs WS2018B</h2></summary>

| Componente | Pino |
| --- | --- |
| NeoPixel (Matriz de LEDs) | GPIO 7 |

</details>

<details><summary><h2>LED RGB</h2></summary>

| Componente | Pino |
| --- | --- |
| LED Verde (PWM) | GPIO 11 |
| LED Azul (PWM) | GPIO 12 | 
| LED Vermelho (PWM) | GPIO 13 |

</details>

<details><summary><h2>Buzzers</h2></summary>

| Componente | Pino |
| --- | --- |
| Buzzer 1 (PWM) | GPIO 21 |
| Buzzer 2 (PWM) | GPIO 10 |

</details>

<details><summary><h2>Botões</h2></summary>

| Componente | Pino |
| --- | --- |
| Botão A | GPIO 5 |
| Botão B | GPIO 6 |

</details>
