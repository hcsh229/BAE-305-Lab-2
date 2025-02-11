# For Good Measure: Basic Circuits
Group Members: Heath Shewmaker and Terence Redford

Submitted on: 2/10/2025
# Introduction Summary:
The aim of this project was to build one series and one parallel circuit, and then use physical measurements taken by a Digital Multimeter to verify theoretical values calculated by using Thevenin's and Norton's theorems. This lab was also related to verifying the accuracy of Kirchoff’s voltage and current laws, which are the basis for calculating Thevenin and Norton equivalent circuits. It also served as additional practice for measuring resistance, voltage and current through circuit elements using the DMM. Additionally, we were able to get some hands-on experience with a common electrical practice in the form of soldering. 
# Methods/Tests:
step 1) The resistances of each of the resistors were verified, using the DMM, before use in the circuits to ensure functionality and calculations. The results of the measurements are tabulated with respect to the expected values below:

 ![image](https://github.com/user-attachments/assets/d354bc77-2ff8-4077-a4e6-79b727d70b15)

 Figure 1: Measured Resistance vs Expected Resistance for each resistor used in Lab 2.

Step 2) A series circuit was soldered to the prototyping solder board. The circuit was composed of a 1k Ohm resistor, a 2.2k Ohm resistor, and a 5.1k Ohm resistor, which were all connected to a DCPS set to supply 10 Volts. Below is an image of the circuit after soldering.

![image](https://github.com/user-attachments/assets/ab398a3f-e787-4e19-8520-d0ced78662e3)

Figure 2: Series circuit composed of 3 resistors soldered to a prototyping board. 

Step 3) The voltage drops across each of the resistors were measured using the DMM and Tabulated, shown in the results section. Included in this was also a reading of the current in the circuit, obtained by putting the DMM in series with any part of the circuit.
Step 4) A parallel circuit was then built on a breadboard with a 4.7k Ohm resistor in series with a parallel combination containing 3 branches. The first branch was a series combination of resistors measuring 6.8k Ohms and 15k Ohms respectively. The second branch was a 220k Ohm resistor and the third branch was a 2.2k Ohm resistor. The DCPS was used as the voltage source and set to deliver 12 Volts. This was verified using the DMM.

 ![image](https://github.com/user-attachments/assets/7497053a-3251-4856-93d3-c07949a14797)

 Figure 3: Parallel circuit composed of 5 resistors using a breadboard. 

Step 5) The currents and voltages through each of the resistors were measured using the DMM and can be found in the results section.
Step 6) To simulate the Norton resistance the 2.2k Ohm resistance was removed, and the leads of the DCPS were disconnected and replaced with a short circuit to connect all the components. Using the DMM the Norton resistance was measured.

# Results:
For the series circuit, the voltage drops across each resistor are tabulated below and compared to an expected value (calculated using Ohms law).

 ![image](https://github.com/user-attachments/assets/d56e5461-c541-449e-8c4c-de13353cde80)

 Figure 4: Voltage drop vs Expected Voltage drop with respect to each resistor in the series circuit.

For the parallel circuit, the current and voltage drop for each of the components were as follows:

![image](https://github.com/user-attachments/assets/daf3177b-5427-45b3-92d5-9e5c02b7407f)

Figure 5: Measured Current and Voltage drop vs Expected Voltage drop for each resistor in the parallel circuit.

The method used to calculate the theoretical Thevenin Voltage and Resistance is shown below: 

![image](https://github.com/user-attachments/assets/6ea4b6c3-aec5-4bf0-942a-2bd32faa2665)

Figure 6: Thevenin Voltage and Resistance Calculations

Measured values of the actual Thevenin Voltage and Resistance are shown below:

  ![image](https://github.com/user-attachments/assets/f4aaa074-5ecd-4a21-acd9-408c29beb86d)

  Figure 7: Actual Thevenin Voltage and Resistance

# Discussion:
Discussion Question 1: Are the measured Currents in agreement with Kirchoff’s Current law?

We expected that the incoming current of 1.8 milliamps would be split completely into each of the 3 branches without any current loss. However, when we added our measurements for currents exiting the junction, we only managed to account for 1.786 milliamps. This slight variation could either be explained by current that was used by the DMM or errors in rounding and measurement.

Discussion Question 2: Compare the measured Voltages and the calculated Values. Are these in agreement with Kirchoff’s voltage law?

The values we calculated were very close to the measurements we took, although there is some error. This is because the resistors do not have the exact nominal resistance specified so the voltage may have small fluctuations.

Discussion Question 3: Calculate the power delivered by the power supply and the power dissipated by every resistor. Is the power delivered by the power supply equal to the total power dissipated?

We calculated an expected power output from the power supply by taking I1 and multiplying it by the source voltage of 12V. This yielded a power output of 21.6 milliWatts. This was compared to the sum of V2/R terms, which was calculated to be a power dissipation of 21.3 milliWatts. Although these values are not identical, they are within a reasonable range of one another, indicating that any variations are likely from random measurement errors or limiting factors such as the internal resistance of the DMM or non-nominal resistors.

Discussion Question 4: Using circuit analysis, calculate RTH, IN, and VTH, and compare them with the measured values. Are the calculated values in agreement with the measured values?

We calculated RTH to be 3799 Ohms, VTH to be 9.156V, and IN to be 2.41 milliAmps. These values were close enough to the measured values that, once again, we justified any variances to be created by errors.
# Conclusion:
The most valuable takeaway from this Lab is that KVL, KCL, and the Thevenin and Norton theorems are fundamentally accurate within any circuit. However, they are also ideal cases for circuits that have no flaws or interactions with the environment and measurement tools. As such they are best thought of as theoretically accurate, but not necessarily exactly true in a circuit. Because of this, we learned to take the DMM reading to heart, as it does not lie. Aside from the theoretical knowledge we gained, we also learned valuable practical skills like soldering techniques, including which solder types are safe for use. We also got to further practice measuring currents using the DMM, which will become a critical tool for understanding other circuits. 
