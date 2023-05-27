# -Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger
  <p align="center">
    <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/c601b95fd512c4e891db4346fd5a141e44b59230/Final%20Schematic.JPG" width=100% height=100%>
  </p>
  <p align="center">
    Final Schematic
  </p>  
  
  <p align="center">
    <img src="https://github.com/Kai-i-Tam/-Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/768766ca78714102fe0fd5464d35948f37470776/20220329_203334.jpg" width=100% height=100%>
  </p>
  <p align="center">
    The final form of the prototype.
  </p>  
  
  <p align="center">
    <img src="https://github.com/Kai-i-Tam/-Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/768766ca78714102fe0fd5464d35948f37470776/20220329_120127.jpg" width=100% height=100%>
  </p>
  <p align="center">
    Getting some Sun readings and Converter performance.
  </p>
  
  ## Project Description
  This is one of the lab projects done in my MSEE class. One of my favourites. Have the chance to calculate, modeling, build, test the circuit.
  Closed-Loop Photovoltaic SEPIC Power Supply and Battery Charger, with Built in Digital PID Compensator.

  **Project 1 Direct Energy Transfer System**  
  The very first project require us to get the actual Solar Panel Value under the Sun, Short Circuit Current, Open Circuit Voltage.  
  Then turn those values into mathmetical model for simulations in LTSpice.  
  
  - [Project 1 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%201%20Procedure.pdf)
  - [Project 1 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205716%20Project%201%20Direct%20Energy%20Transfer%20System%20-%20Kai%20Tam.pdf)  
  
  **Project 2 Software Tools and Pulse-Width Modulator**  
  The second project require us to get the launchpad ready on the prototype board.  
  In Software, setting up the decided switching frequency and duty cycles. Then verified with Digilent AD2 or any Oscilloscopte.  
  
  - [Project 2 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%202%20Procedure.pdf)
  - [Project 2 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205716%20Project%202%20Software%20Tools%20and%20Pulse-Width%20Modulator%20-%20Kai%20Tam.pdf)  

  **Project 3 Open-Loop DC-DC Converter**  
 The third one require us the do the analysis of the circuit, including Volt Second Balance, Charge Balance.  
 Since we had got the Solar Panel Value from Project 1, we will use those as Input values of the SEPIC, with our decided switching frequency, we then found out the optimum values of all elements.  
 
 Once we have decided the Inductor Values, we will then construct our own (hand build),   
 Using the Network Analyzer from Digilent AD2, we can do a sweep and get the Bode Plot of the Inductors.  
 
 We also have to design and hand build our own Current measuring transformer which reading the Drain Current of the MOSFET.  
 Putting everything together on a quick prototype board (totally disregard EMI), we measure the actual value of how the circuit behave in Open Loop.  
 
 Also using LTSpice to simulate the actual Solar Panel and Circuit behavior in Average Model.
 Getting the "close enough" duty cycle for Maximum Power Transfer is the objective for this project. which is approximately 0.45
 
  - [Project 3 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%203%20Procedure.pdf)
  - [Project 3 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205716%20Project%203%20Open-Loop%20DC-DC%20Converter%20-%20Kai%20Tam.pdf)  
  
  **Project 4 Converter Small-Signal AC Transfer Functions**  
  Description here
  - [Project 4 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%204%20Procedure.pdf)
  - [Project 4 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205717%20Project%204%20Converter%20Small-Signal%20AC%20Transfer%20Functions%20-%20Kai%20Tam.pdf)  

  **Project 5 Closed-Loop Voltage Regulator**  
  Description here
  - [Project 5 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%205%20Procedure.pdf)
  - [Project 5 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205717%20Project%205%20Closed-Loop%20Voltage%20Regulator%20-%20Kai%20Tam.pdf)  
  
  **Project 6 Maximum Power Point Tracking**  
  Description here
  - [Project 6 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%206%20Procedure.pdf)
  - [Project 6 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205718%20Project%206%20Maximum%20Power%20Point%20Tracking%20-%20Kai%20Tam.pdf)  

  **Project 7 Battery Management**  
  Description here
  - [Project 7 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%207%20Procedure.pdf)
  - [Project 7 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205718%20Project%207%20Battery%20Management%20-%20Kai%20Tam.pdf)  
  
  
  ## Pros
  Get the vertical design experience of Solar Power Converter.
  One of the greatest adventage of this lab is scalable, we can later using this as template to build a larger Solar Power Chargers.
  
  ## Cons
  Never got a chance to actually design the PCB based on what I have done on the prototype.
    
  ## Note to Future Development
  If I will do the PCB of this projects, some of the measurement would be better because it would be less ESR and ESL. Switching Noise will be less and efficiency would definitly gone up.
  It would be nice to sell it as a kit for future students.
  
  ## PCB
    Reserved

