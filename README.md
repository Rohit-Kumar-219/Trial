# Hand Gesture Recognition
   Shristi 2020

## Abstract
   
   The aim of the project is to create hand bot which can replicate the movements of hands of the person who is interacting with the bot, with the help of image processing. This project is a combination of live motion detection and gesture identification.
   

## Motivation 
   The motivation is to create a bot that can copy the movements of an original hand. With further motivations this bot can be upgraded to an artificial hand. This model is just to understand the coordination between the human and robotic actions. This bot aims in maximising of the patterns of the human hand, to replicate it. 

## Components
   
   - 2x Arduino 
   - 2x NRF module
   - 5x Servomotor
   - Laptop (for image processing)
   - 5x 10k Resistors
   - 9V Batteries
   - 2x Breadboard
   - Jumpers
   - Braid wire (for the stifness of the  fingures of the bot)
   - Copper wire

## Workflow
![Workflow](https://static-01.hindawi.com/articles/tswj/volume-2014/267872/figures/267872.fig.001.jpg)

## Mechanical aspect of the design
### Structure
   The main frame of the bot is 3d printed. Apart from the 3d frame, the structure has grooves which are made to mount the motors and the breadboard inside the model. Braid wire is used to provide stiffness to the fingures of the bot whereas copperwire is used to connect the tip of the fingure to the rotors of the motors. In total the bot will contain the motors, arduino, reciever nrf module and a battery. The transitor portion (i.e. the arduino and the transmitter nrf module) will be attached to the laptop, for identifying the pattern and sending the signals to the bot.
