# -Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger

  <p align="center">
    <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Solar%20Power%20System.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Block Diagram
  </p>  
  
  <p align="center">
    <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/c601b95fd512c4e891db4346fd5a141e44b59230/Final%20Schematic.JPG" width=100% height=100%>
  </p>
  <p align="center">
    Final Schematic
  </p>  
  
  <p align="center">
    <img src="https://github.com/Kai-i-Tam/-Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/768766ca78714102fe0fd5464d35948f37470776/20220329_203334.jpg" width=80% height=80%>
  </p>
  <p align="center">
    The final form of the prototype.
  </p>  
  
  <p align="center">
    <img src="https://github.com/Kai-i-Tam/-Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/768766ca78714102fe0fd5464d35948f37470776/20220329_120127.jpg" width=80% height=80%>
  </p>
  <p align="center">
    Getting some Sun readings and Converter performance.
  </p>
  
  ## Project Description
  This is one of the lab projects done in my MSEE class. One of my favourites. Have the chance to calculate, modeling, build, test the circuit.
  Closed-Loop Photovoltaic SEPIC Power Supply and Battery Charger, with Built in Digital PID Compensator.
  
  ___  

  **Project 1 Direct Energy Transfer System**  
  > Operate and model PV panel 
  > - Measure i-v curve of PV panel, in full sun and also with partial shading
  > - Measure power when PV panel charges battery
  > - Develop Spice model of PV panel
  > - Figure out How much more power could be obtained via MPPT.
  
  - [Project 1 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%201%20Procedure.pdf)
  - [Project 1 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205716%20Project%201%20Direct%20Energy%20Transfer%20System%20-%20Kai%20Tam.pdf)  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/L1%20BodePlot%2064%20Turns%20470uH%20d.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Inductor Bode Plot
  </p>  
  
  ___
  
  **Project 2 Software Tools and Pulse-Width Modulator**  
  > Produce PWM signal with programmable switching frequency and duty cycle.
  > - Launchpad development board with TMS320F28027 processor
  > - Download Code Composer Studio, install on your local computer, load PWM generator project  
  
  > Measure PWM signal with Analog Discovery 2: 2 channel 50 MHz scope  
  > - Download Waveforms, capture oscilloscope waveforms on your computer
  > - Begin construction of your converter prototype on perfboard
    
  - [Project 2 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%202%20Procedure.pdf)
  - [Project 2 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205716%20Project%202%20Software%20Tools%20and%20Pulse-Width%20Modulator%20-%20Kai%20Tam.pdf)  
  
  ___
  
  **Project 3 Open-Loop DC-DC Converter (SEPIC)**  
  > Construct and test SEPIC power stage
  > - DC power supply drives converter input
  > - Resistive load
  > - Launchpad supplies PWM output
  > - Design and construction of inductors
  > - Build SEPIC power stage
  > - Build gate driver
  > - Incorporate LDO to produce 5 V for gate driver
  > - Measure Vpv and Ibatt vs. D, for battery output and PV input
 
  - [Project 3 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%203%20Procedure.pdf)
  - [Project 3 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205716%20Project%203%20Open-Loop%20DC-DC%20Converter%20-%20Kai%20Tam.pdf)  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Project%203%20LTSpice.JPG" width=80% height=80%>
  </p>
  <p align="center">
    LTSpice .sch of Averaged SEPIC
  </p>  
  
  ___
  
  **Project 4 Converter Small-Signal AC Transfer Functions**  
  > Measure and model SEPIC transfer function.  
  > - Use AD2 to measure control-to-output transfer function with DC power supply at input and one resistor loading output.  
  > - Damp internal resonance of SEPIC if necessary  
  > - Verify with simulation and analysis  

  - [Project 4 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%204%20Procedure.pdf)
  - [Project 4 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205717%20Project%204%20Converter%20Small-Signal%20AC%20Transfer%20Functions%20-%20Kai%20Tam.pdf)  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/bd7eb599123ddcdca41bd856def27434bbf4e436/Project%204%20Damped.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Gvd(s) (damped)
  </p>  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/bd7eb599123ddcdca41bd856def27434bbf4e436/Project%204%20AD2%20Damped.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Gvd / Vm (with damping elements)
  </p>  
  
  ___
  
  **Project 5 Closed-Loop Voltage Regulator**  
  > Use results of Exp. 4 to design and implement closed loop voltage regulation
  > - Design conventional analog compensator
  > - Implement equivalent digital compensator in code
  > - Measure and verify loop gain using AD2

  - [Project 5 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%205%20Procedure.pdf)
  - [Project 5 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205717%20Project%205%20Closed-Loop%20Voltage%20Regulator%20-%20Kai%20Tam.pdf)  
    
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/bd7eb599123ddcdca41bd856def27434bbf4e436/Project%205%20LTSpice.JPG" width=80% height=80%>
  </p>
  <p align="center">
    D vs. V(out) in LTSpice
  </p>  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/bd7eb599123ddcdca41bd856def27434bbf4e436/Project%205%20Matlab.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Compensated and Uncompensated Loop Gain (Tu, T), optimized Phase Margin
  </p>  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/bd7eb599123ddcdca41bd856def27434bbf4e436/Project%205%20AD2.JPG" width=80% height=80%>
  </p>
  <p align="center">
    Compensated Loop Gain (T)
  </p> 
  
  ___
  
  **Project 6 Maximum Power Point Tracking**  
  > Design and implement MPPT
  > - Implement and calibrate current sensor circuit.
  > - Develop and demonstrate MPPT code

  - [Project 6 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%206%20Procedure.pdf)
  - [Project 6 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205718%20Project%206%20Maximum%20Power%20Point%20Tracking%20-%20Kai%20Tam.pdf)  
  
  <p align="center">
  <img src="https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/bd7eb599123ddcdca41bd856def27434bbf4e436/Project%206%20Matlab.JPG" width=80% height=80%>
  </p>
  <p align="center">
    MATLAB/Simulink model
  </p> 
  
  ___
  
  **Project 7 Battery Management**  
  > Design and implement battery charge control
  > = MPPT for fast charging
  > - Voltage regulation (charge taper)
  > - When charging current falls below a threshold, terminate charging  
   
  - [Project 7 Requirement](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/main/Experiment%207%20Procedure.pdf)
  - [Project 7 Report](https://github.com/Kai-i-Tam/Closed-Loop-Photovoltaic-SEPIC-Power-Supply-and-Battery-Charger/blob/d47ca51a6252e8a47e37fec5e7a193627b1395b2/ECEA%205718%20Project%207%20Battery%20Management%20-%20Kai%20Tam.pdf)  
    
  ___
  
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

