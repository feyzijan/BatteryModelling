# Battery Modelling
 
 This project aims to investigate the behaviour of lithium ion batteries in order to create models that simulate the behaviour of a lithiom-ion mattery. The complex electrochemical and physical processes inside battery will be approximated by simple electrical components and circuits that gradually becomes more Complex.
 Here is how the project is divided up
 
Part 1: A simple Thevenin model: Voltage source and single constant Resistor. Taking current profile as an input and outputting voltage, using 'Coulomb counting' to track the SOC(State of Charge) of the battery.
- Discharge data at a single temperature is used

Part 2: A first order ECN(Equivalent Circuit Network Model): Voltage source + Resistor in series with a Capacitor and Resistor in parallel. Component values are functions of time, SOC, current, and temperature. 
Temperature and Current are taken as model inputs. 
- Discharge data at three different temperatures are used


Part 3: Improvement of the model in Part 2 with thermal coupling, where the cell is assumed to be a single lumped thermal mass, so that Temperature is now predicted by the model as well.
Only Current is taken as an imput

Part 4: Improvement of the model in Part 3 with a degradation mechanism : Cycle and Calender Ageing.


