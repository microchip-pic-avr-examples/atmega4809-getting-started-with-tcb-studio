[![MCHP](images/microchip.png)](https://www.microchip.com)

# Getting Started with Timer/Counter Type B (TCB) Examples (Microchip Studio)

  This repository contains examples of bare metal source code for Timer/Counter Type B (TCB) as described in [TB3214 - Getting Started with Timer/Counter Type B (TCB)](https://ww1.microchip.com/downloads/en/Appnotes/TB3214-Getting-Started-with-TCB-DS90003214.pdf) document from Microchip. The repository contains an Atmel Studio Solution with multiple projects inside:

  * [<strong>Using TCB in 8-bit PWM Mode:</strong>](Using_TCB_in_8-bit_PWM_Mode) This use case shows how to generate an 8-bit PWM signal with 1 kHz frequency and 50% duty cycle on a GPIO pin (for more details, see [<strong>Using TCB in 8-bit PWM Mode</strong>](Using_TCB_in_8-bit_PWM_Mode))
  * [<strong>Using TCB in Sleep Mode:</strong>](Using_TCB_in_Sleep_Mode) This use case shows how to configure the TCB to produce an interrupt every second that wakes up the device from sleep and toggles an LED (for more details, see [<strong>Using TCB in Sleep Mode</strong>](Using_TCB_in_Sleep_Mode))
  * [<strong>Using TCB in Time-out Check Mode:</strong>](Using_TCB_in_Time-out_Check_Mode) This use case shows how to configure the TCB to toggle an LED if the input signal is longer than the time-out period (for more details, see [<strong>Using TCB in Time-out Check Mode</strong>](Using_TCB_in_Time-out_Check_Mode))

## Related Documentation
More details and code examples on the ATMEGA4809 can be found at the following links:
- [TB3214 - Getting Started with Timer/Counter Type B (TCB)](https://ww1.microchip.com/downloads/en/Appnotes/TB3214-Getting-Started-with-TCB-DS90003214.pdf)
- [ATMEGA4809 Product Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [ATMEGA4809 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=atmega4809)
- [ATMEGA4809 Project Examples in START](https://start.atmel.com/#examples/ATMEGA4809XplainedPro)


## Software Used
- Microchip Studio 7.0.2542 or newer [(https://www.microchip.com/mplab/microchip-studio)](https://www.microchip.com/mplab/microchip-studio)
- ATmega_DFP 1.6.364 or newer Device Pack


## Hardware Used
- ATMEGA4809 Xplained Pro [(ATMEGA4809-XPRO)](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)
