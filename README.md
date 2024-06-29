# EmergingSysArch-Tech
Emerging System Architecture &amp; Technology
# 

# Summarize the project and what problem it was solving.
In this project I worked to develop a WiFi compatible thermostat software integrated into the TI CC3220S-LAUNCHXL as described in the scenario 
by SysTec company as a thermostat system that activates an LED when the heat system is being called, with one button for decreasing temperature, 
another button for increasing temperature, and an operative variable for heating system state. This system is also designed to only check a button's
activation every  200ms, update thermostat's local temp every 500ms and update the LED state as well as the server every 1 second with room temperature,
set point temperature, heating system state, and time in seconds since thermostat program activation data. 

# What did you do particularly well?
During this project, I did expectionally well at conceptualizing the procedures involved in the software packages operation. Along with the integration 
of UART, I2C and Timer mechanisms

# Where could you improve?
Although this system was reported as fully functional during deployment, there recurring complications within the CCS execution of this software package
mitigated by resetting the board and playing with the environmental configuratuions. From this experience, I would say that I would greatly benefit from 
furthering my understanding of how Code Composer Studio interacts with C++ compilers and the TI C3220S boards.

# What tools and/or resources are you adding to your support network?
From my work in the TI C3220S-LAUNCHXL, I have discovered a multitude of information available in the TI Reference for embedded systems development.

# What skills from this project will be particularly transferable to other projects and/or course work?
I found the development of state machines particularly insightful and I will absolutely be applying these architectures again in the near future.

# How did you make this project maintainable, readable, and adaptable?
I kept this project maintainable, readable, and adaptable by strategic spacing between sections of code, concise commenting 
to allow developers to understand procedures at a glance, and modulization of key operations to allow core processes to be updated with ease.
