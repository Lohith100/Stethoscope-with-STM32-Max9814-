# ELectronic Stethoscope 
## _Made with STM32f407vgt6 , Max9814_

A simple electronic stethoscope made with stm32 dicovery board and uses max9814 as pre-amplifier directly comes with an analog microphone and used PAM8403 amplifier connected to speaker to listen audio.  
## Requirements
- STM32f407vgt6 discovery board
- MAX9814 pre-amp module
- PAM8403 amplifier module
- 1w mini speaker 
- STM32 CubeIDE 


## Features

- DMA for audio data transfer , collection from microphone to STM32
- Can be integrate with matlab using USART to do further audio processing 
- Clearly audible heart sound from speaker with amplification because of PAM8403 module


## Connections

-Common ground the GAIN, GND of Max9814 , Gnd of PAM8403 ,STM32

- 3.3v Rail for max9814,stm32 & 5v for PAM8403
- PA4 of STM32 connected to PAM module L or R IN 
- connect speaker to L or R out of pam8403


## Images

![Prototype_stm32](https://github.com/user-attachments/assets/96f70834-2549-4961-8821-218f63e517d8)
## Results of audio from Matlab
![spectrogram](https://github.com/user-attachments/assets/f7a0bd3a-c835-4d0d-8657-14c3b5f6658d)
![plot](https://github.com/user-attachments/assets/e4329b8b-7cc6-4003-bbed-9988afb50641)

