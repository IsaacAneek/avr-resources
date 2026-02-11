# Basic Electronics
### Pull up and Pull down Resistors
  - [Pull Up Resistor: What is it (And How Does it Work)?](https://www.electrical4u.com/pull-up-resistor/)
  - [Pull-up and Pull-down Resistors](https://www.circuitbasics.com/pull-up-and-pull-down-resistors/)
  - [The Pull-Up Resistor: How It Works and Choosing a Value](https://www.build-electronic-circuits.com/pull-up-resistor/)
  - [Pull-up Resistors](https://www.electronics-tutorials.ws/logic/pull-up-resistor.html)
### Open Drain/Open Collector Configuration
  - [What is Open Drain : Configuration & Its Applications](https://www.watelectronics.com/open-drain/)
  - [Push-pull/Open drain;pull-up/pull-down](https://electronics.stackexchange.com/questions/28091/push-pull-open-drain-pull-up-pull-down)
  - [What is an Open Drain : Configuration & Its Working](https://www.elprocus.com/what-is-an-open-drain-configuration-its-working/)

# AVR Core Resources
### Interrupts
- [Interrupts and 16-bit Timer/Counter 1: ATmega Interrupts](https://www.arxterra.com/10-atmega328p-interrupts/)
- [Interrupts](https://gammon.com.au/interrupts)
### Bootloader
- [Simple AVR Bootloader Tutorial](https://github.com/m3y54m/simple-avr-bootloader)
### UART
- Basics of UART
  - [Back to Basics: The Universal Asynchronous Receiver/Transmitter (UART)](https://www.allaboutcircuits.com/technical-articles/back-to-basics-the-universal-asynchronous-receiver-transmitter-uart/)
  - [UART Baud Rate: How Accurate Does It Need to Be?](https://www.allaboutcircuits.com/technical-articles/the-uart-baud-rate-clock-how-accurate-does-it-need-to-be/)
  - [AVR Atmega328P UART](http://www.rjhcoding.com/avrc-uart.php)
### I2C
- Basics of I2C
  - [I2C Wikipedia](https://en.wikipedia.org/wiki/I%C2%B2C#)
  - [How I2C Interface Functions?](https://digilent.com/blog/i2c-how-does-it-work/)
  - [I2C devices connected to Arduino UNO (Atmega328p)](https://github.com/abmj01/ATmega328p_I2C)
  - [Understanding I2C](https://www.youtube.com/watch?v=CAvawEcxoPU)
  - [Programming AVR I2C interface](https://embedds.com/programming-avr-i2c-interface/)
  - [I2C Communication Concept : Arduino / ATmega328p](https://www.arnabkumardas.com/arduino-tutorial/i2c-concept/)
  - [Using the I2C Interface on the ATmega328P](https://ece-classes.usc.edu/ee459/library/documents/I2C.pdf)
  - [Basics of I2C communication | Hardware implementation of I2C bus](https://www.youtube.com/watch?v=pbqk5yqbfuw)
  - Related Info
    - Bus Capacitance in I2C
      - [Parasitic Capacitance](https://en.wikipedia.org/wiki/Parasitic_capacitance)
      - [I2C pull up resistance, rise time and bus capacitance discussion](https://fastbitlab.com/i2c-pull-up-resistance-rise-time-and-bus-capacitance-discussion/)
      - [How to calculate the I2C bus capacitance](https://community.nxp.com/t5/Kinetis-Microcontrollers/How-to-calculate-the-I2C-bus-capacitance/m-p/1079510)
      - [What is Bus capacitance?](https://www.edaboard.com/threads/what-is-bus-capacitance.211149/)
      - [I2C Design Mathematics: Capacitance and Resistance](https://www.allaboutcircuits.com/technical-articles/i2c-design-mathematics-capacitance-and-resistance/)
      - [What is Bus capacitance in I2C? How it limits number of devices can be connected to the bus?](https://electronics.stackexchange.com/questions/494718/what-is-bus-capacitance-in-i2c-how-it-limits-number-of-devices-can-be-connected)
    - Bus Arbitration in I2C
      - [Basics of I2C : Advanced Topics](https://www.ti.com/content/dam/videos/external-videos/en-us/8/3816841626001/6243124608001.mp4/subassets/adcs-introduction-to-i2c-advanced-topics-presentation.pdf)
      - [Bus Arbitration](https://www.esacademy.com/en/library/technical-articles-and-documents/miscellaneous/i2c-bus/general-introduction/bus-arbitration.html)
      - [Getting Started with I2C: What is Bus Arbitration](https://embeddedwala.com/Blogs/DigitalCommunication/Getting-Started-with-I2C:-What-is-Bus-Arbitration)
    - Clock Streching
      - [Getting Started with I2C: What is Clock Stretching](https://embeddedwala.com/Blogs/DigitalCommunication/Getting-Started-with-I2C:-What-is-Clock-Stretching)
      - [STM32 I2C Lecture 13: Clock Stretching](https://fastbitlab.com/stm32-i2c-lecture-13-clock-stretching/)
- I2C Implementation
  - [Interfacing an accelerometer over I2C with the ATmega328p](https://timothymcpherson.wordpress.com/2015/09/07/interfacing-over-i2c-with-the-atmega328p/)
  - [Fast SSD1306 OLED drawing with I2C bit banging](https://bitbanksoftware.blogspot.com/2018/05/fast-ssd1306-oled-drawing-with-i2c-bit.html)
  - [Tiny Graphics Library for use with an I2C 128x64 OLED display on an ATtiny85 <b>[SH1106]</b>](http://www.technoblogy.com/show?23OS)
  - [Tiny Function Plotter <b>[SSD1306]</b>](http://www.technoblogy.com/show?2CFT)
  - [Code for the Tiny Function Plotter](http://www.technoblogy.com/list?2CWV)
  - [Adding two OLED displays to your Arduino logger (without a library)](https://thecavepearlproject.org/2020/11/15/adding-two-oled-displays-to-your-arduino-logger-with-no-library)
  - [Debugging SSD1306 Display Problems](https://iotexpert.com/debugging-ssd1306-display-problems)
### PWM
- [Secrets of Arduino PWM](https://docs.arduino.cc/tutorials/generic/secrets-of-arduino-pwm)
- [What the heck is double buffering, and why should you care?](https://doctor-pasquale.com/2025/04/29/skipped-toggles-using-atmega328p-timer-counter-1-in-ctc-mode)
- [Power LED Dimmer using ATmega32 Microcontroller](https://circuitdigest.com/microcontroller-projects/power-led-dimmer-using-atmega32-pwm)
- [What is PWM (Pulse Width Modulation)](https://circuitdigest.com/tutorial/what-is-pwm-pulse-width-modulation)
### RTOS
- [Write a Premptive Task Schedualar for AVR](https://kevincuzner.com/2015/12/31/writing-a-preemptive-task-scheduler-for-avr)
- [Multitasking the Arduino Part-1](https://learn.adafruit.com/multi-tasking-the-arduino-part-1)
- [How to Build a Schedular](https://homes.cs.washington.edu/~shwetak/classes/ee472/notes/SchedImplementation.pdf)
- [Premptive version of RIOS for AVR](https://www.cs.ucr.edu/~vahid/rios/rios_avr.htm)
- [RIOS : A cooperative (simple or state-machine based) schedular](https://www.cs.ucr.edu/~vahid/rios)
- [Cooperative vs. Preemptive: a quest to maximize concurrency power](https://medium.com/traveloka-engineering/cooperative-vs-preemptive-a-quest-to-maximize-concurrency-power-3b10c5a920fe)
- [What are “co-operative” and “pre-emptive” scheduling algorithms?](https://www.rapitasystems.com/blog/what-are-co-operative-and-pre-emptive-scheduling-algorithms)
### AVR Communities
- [AVR Freaks community](https://www.avrfreaks.net)
### AVR Simulator
- [AVR Sim (Web)](https://jonopriestley.github.io/avrsim)
### AVR C
- [Getting started with AVR programming](https://github.com/m3y54m/start-avr)
- [Mixing C and AVR Assembly](https://www.bitbanging.space/posts/mixing-c-and-assembly-for-avr-microcontrollers)
- [AVR Optimization #1 - Avoid floating-point and other considerations](https://www.bitbanging.space/posts/avr-code-optimization)
- [AVR-GCC](https://gcc.gnu.org/wiki/avr-gcc)
- [Developing in C for the ATmega328: Multitasking](https://wellys.com/posts/avr_c_step6/)
- [Hardware Debug: Using gdb to Debug](https://wellys.com/posts/avr_c_gdb/#)
## AVR Assembly Resources
### AVR-GCC Inline Assembly
- [How to use Inline Assembly in C code](https://gcc.gnu.org/onlinedocs/gcc/Basic-Asm.html)
- [Inline Assembler in AVR-GCC (Deutsch)](https://rn-wissen.de/wiki/index.php/Inline-Assembler_in_avr-gcc)
- [Assembler and Inline Assembler (Deutsch)](https://www.mikrocontroller.net/articles/AVR-GCC-Tutorial/Assembler_und_Inline-Assembler)
- [Assembler Instructions with C Expression Operands](https://gcc.gnu.org/onlinedocs/gcc/Extended-Asm.html)
- [AVR LibC Inline Assembly](https://www.nongnu.org/avr-libc/user-manual/inline_asm.html)
- [AVR-GCC Inline Assembler Cookbook AVR LibC](https://avrdudes.github.io/avr-libc/avr-libc-user-manual-2.2.0/inline_asm.html)
- [GCC-AVR Inline Assembler Cookbook](https://web.stanford.edu/class/ee281/projects/aut2002/yingzong-mouse/media/GCCAVRInlAsmCB.pdf) [Deprecated]
### AVR Assembly
- [Development of a Blink driver in AVR Assembler](https://github.com/mytechnotalent/Reverse-Engineering?tab=readme-ov-file#hacking-bits-course-chapter-7-blink-driver-in-c)
- [AVR Instruction set Manual](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/ReferenceManuals/AVR-InstructionSet-Manual-DS40002198.pdf)
- [Arduino UNO LED Blink Assembly Program](https://atmega32-avr.com/explore-avr-assembly-language)
- [AVR microcontroller programming with avr-libc and the GNU tool chain](https://github.com/matthew-macgregor/avr-assembly-examples)
- [AVR Assembly Programming Cheatsheet](https://gist.github.com/jfamousket/6bb36547fbfc2669c87ff7f1cbe47a44)
- [AVR Assembly examples](https://github.com/matthew-macgregor/avr-assembly-examples)
- [AVR assembly and debugging with VSCode and Platform IO](https://www.youtube.com/watch?v=BM-w1pcekxA)
- [AVR ASM Tutorials](http://rjhcoding.com/avr-asm-tutorials.php)
- [Beginner's AVR ASM](https://kitsandparts.com/tutorials/assemblers/BeginnersAVRasm.pdf)
- [AVR Assembler 101](https://www.codeproject.com/Articles/712610/AVR-Assembler)
- [AVR Assembly Language Tutorial for Beginners](https://studylib.net/doc/27106186/avr-assembly-beginner-en)
- [AVR Resources](https://avr-tutorials.com/general/avr-resources)
- [Beginners Introduction to the Assembly Language of ATMEL-AVR Microprocessors](https://moodle.unach.edu.ec/pluginfile.php/4480410/mod_resource/content/2/AVR-Assembler-Tutorial.pdf)
- [AVR Assembler for Complex Projects](https://kitsandparts.com/tutorials/assemblers/AdvancedAVRASM2.pdf)
- [AVR: Architecture, Assembly & Reverse Engineering](https://hackaday.io/course/176685-avr-architecture-assembly-reverse-engineering)

## Similar sources
- [Crack you Embedded Interview](https://github.com/imsunilvaghela/TheEmbeDEADInterview)
- [Helping you prepare for your upcoming embedded interviews](https://github.com/Bassel20/Embedded-Systems-Interview-Questions-Answers?tab=readme-ov-file)
- [AVR Programming](https://github.com/hexagon5un/AVR-Programming)
- [Learn Embedded Systems](https://github.com/erinjense/Learn-Embedded-Systems)
- [TheEmbeddedNewTestament](https://github.com/theEmbeddedGeorge/theEmbeddedNewTestament.github.io/tree/master)
- [AwesomeEmbedded](https://github.com/nhivp/Awesome-Embedded)
- [Awesome-C](https://github.com/uhub/awesome-c)
- [Awesome Embedded Systems](https://github.com/embedded-boston/awesome-embedded-systems)

### <b>All CREDITS GO TO THE RESPECTIVE OWNERS/AUTHORS</b>
