# Plano de Aula - Robótica com Arduino

## Aula 1: Introdução ao Arduino e Controle de LED

### **Objetivo Geral**
Capacitar os alunos a compreenderem os conceitos básicos de eletrônica e programação com Arduino, utilizando metodologias expositivas e Problem-Based Learning (PBL) para criar um olho robótico simples.

### **Objetivos Específicos**
- Apresentar a plataforma Arduino e suas aplicações.
- Ensinar os alunos a montar um circuito básico utilizando um LED e um resistor.
- Introduzir os conceitos de programação no ambiente Arduino IDE.
- Aplicar a metodologia PBL para estimular a resolução de problemas práticos.

### **Materiais Utilizados**
- 1 Placa Arduino Uno
- 1 Protoboard
- 1 LED
- 1 Resistor de 220 ohms
- 2 Jumpers
- Computador com Arduino IDE instalado

### **Metodologia**
1. **Exposição Teórica**
   - O que é o Arduino e como ele funciona.
   - Introdução aos componentes eletrônicos básicos.
   - Conceitos de corrente elétrica, resistência e circuitos.

2. **Mãos na Massa - Montagem do Circuito**
   - Conectar o LED e o resistor ao protoboard.
   - Ligar o circuito à placa Arduino usando os jumpers.

3. **Programação no Arduino IDE**
   - Explicação sobre a estrutura do código Arduino (setup e loop).
   - Digitação e execução do código para acender e apagar o LED.
   
   ```cpp
   void setup() {
     pinMode(13, OUTPUT); // Define o pino 13 como saída
   }

   void loop() {
     digitalWrite(13, HIGH); // Liga o LED
     delay(1000); // Espera 1 segundo
     digitalWrite(13, LOW); // Desliga o LED
     delay(1000); // Espera 1 segundo
   }
   ```

4. **Desafio PBL - Criando um Olho Robótico**
   - Os alunos deverão modificar o circuito e o código para simular um olho robótico piscando.
   - Eles devem propor soluções para aprimorar o efeito, como alterar a frequência do piscar ou adicionar mais LEDs.
   
### **Avaliação**
- Observação da montagem do circuito e correta conexão dos componentes.
- Teste do programa para verificar se o LED pisca corretamente.
- Criatividade e participação na resolução do desafio PBL.

### **Referências**
- Documentação oficial do Arduino: [https://www.arduino.cc/](https://www.arduino.cc/)
- Simulação do circuito no Tinkercad: [Tinkercad Link](https://www.tinkercad.com/things/aonH7dSfRmK)

---

![image](https://github.com/eclipseCJP/arduino_aula1/assets/58758617/8366a548-99ff-4024-89f8-e88a56ca15ea)

