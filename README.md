# CS-350-Emerging-Systems-Architectures-Technologies
Emerging Systems Architectures and Technologies portfolio showcasing Raspberry Pi hardware integration, GPIO programming, PWM, UART communication, and temperature and humidity sensor interfacing with an LCD.

## Project Summary

For this course, I worked on projects involving embedded systems, hardware interfaces, and emerging systems architectures. My thermostat project focused on developing a Python-based control system that interacts with hardware components, including an AHT20 temperature and humidity sensor, LEDs, push buttons, a character LCD, and UART communication. The system uses a state machine to manage off, heating, and cooling modes while displaying temperature and setpoint information. This project helped me understand how software can interact with physical hardware to monitor conditions and respond to user input.

## What I Did Particularly Well

I did particularly well at organizing the thermostat's functionality into separate components and identifying how each hardware device contributes to the overall system. I connected the requirements for temperature monitoring, user input, visual indicators, and serial communication to the software design. I also focused on documenting the system's behavior and considering how the components work together. This helped me approach the project as a complete embedded system rather than simply a Python programming assignment.

## Where I Could Improve

I could improve by performing more systematic hardware testing and troubleshooting each component independently before testing the complete system. I would also like to strengthen my understanding of timing, concurrent execution, GPIO behavior, and error handling in embedded applications. In future projects, I would create a more detailed test plan, document test results, and verify that the software behaves correctly under different operating conditions.

## Tools and Resources I Am Adding to My Support Network

This course strengthened my experience with Python, Raspberry Pi, GPIO libraries, I²C communication, UART serial communication, and state-machine design. I also gained experience using technical documentation, development tools, diagrams, and GitHub to organize and present project work. These resources will help me troubleshoot hardware and software problems, research unfamiliar technologies, and maintain a portfolio that demonstrates my technical abilities.

## Transferable Skills

The most transferable skills from this project include Python programming, debugging, hardware-software integration, requirements analysis, and technical documentation. Understanding how sensors provide data, how control logic processes that data, and how outputs communicate system status will be useful in future computer science courses and software engineering projects. Evaluating hardware capabilities and matching an architecture to application requirements will also help me make informed design decisions.

## Making the Project Maintainable, Readable, and Adaptable

I approached maintainability by separating responsibilities into logical sections for sensor initialization, LED control, LCD management, state transitions, button input, and UART communication. Meaningful variable names, comments, and consistent formatting make the code easier to understand and troubleshoot. Using a state machine provides a structured way to manage operating modes, while separate functions make individual behaviors easier to update. This organization also makes the project more adaptable because hardware configurations or control requirements can be modified without redesigning the entire application.

## Portfolio Artifacts

- `Thermostat.py`
- `Thermostat_State_Machine.pdf` 

