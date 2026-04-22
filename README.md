# Automatic railway crossing system
Automated railway crossing system that:
  Detects approaching trains automatically
  Checks the road is clear before closing
  Controls a gate (servo motor) safely
  Signals road users with Lights(LEDs)
  Runs deterministically using FreeRTOS
**FreeRTOS concepts**  
Uses two semaphores for
    trainApproach
    trainExit   



**Notes**    
Find the main code in the path- core/src/main.h
You can just download this whole and import it to STM32 Cube IDE as an project and run it.
Also .ioc file is given to configure in STM32CubeMX
