# Series Circuit
- Electrons only have one path to flow through.

- More components = more resistance. 
-  Increase resistance = decrease current
- Less current = less bright bulbs.

- If one resistor breaks, (a bulb breaks), the entire series is turned off. 

## Resistance
- Total resistance goes up with each resistor since the current must go through each resistor. 
- Total resistance = sum of all resistors in the series.
- $$R_T=R_1+R_2+R_3...$$
## Current
Current = amount of charge
	Like the flow of water.
A current cant just disappear. 
- Since only one path if some electrons flow through $R_1$, then they have to continue flowing through $R_2$ and so on. 
- Since the current is the same through the entire circuit:
- $$I_T=I_1=I_2=I_3...$$
## Voltage
$$V_T=V_1+V_2+V_3...$$
Ohm's Law. 


# Parallel Circuit
- There are **multiple** paths for the current to flow through. 

- More paths = Less resistance
- Decreases total resistance = Increases total current
- Voltage drop across each element is the same. 

- Allows individual components to have their own switches. 
- Ensures components have the same voltage. 
- Allow for additional components to be added without changing the voltage. 
- If one resistor breaks, the entire series does not turn off. 

## Current
Kirchhoff's Current Rule
$$I_T=I_1+I_2+I_3...$$
## Voltage
- Voltage drop across that resistor must match the battery voltage. 
- $$V_{battery}=V_1+V_2+V_3...$$
## Resistance
- $$I_T=\frac{V}{R_1}+\frac{V}{R_2}$$
- $$\frac{V}{R_{Total}}=V(\frac{1}{R_1}\frac{1}{R_2})$$
- $$\frac{1}{R_{total}}=\frac{1}{R_1}+\frac{1}{R_2}...$$

## Example
What is
1. The total resistance?
	1. $\frac{1}{R_{Total}}=\frac{1}{10}+\frac{1}{20}$ 
	2. $=\frac{2}{20}+\frac{1}{20}=\frac{3}{20}$
	3. $\frac{1}{R_T}=\frac{3}{20}\rightarrow R_T=\frac{20}{3}$ *Flip both at the end.*
2. The total current in the circuit?
	1. $V_T=I_TR_T$
	2. $12=I_t\times6.67$
	3. $I_T=\frac{12}{6.67}=1.18A$ 
3. The current through each of the resistors?
	1. $V=IR$
	2. $I_1=\frac{V_1}{R_1}$
	3. $I_1=\frac{12}{10}=1.2A$
	4. $I_2=\frac{12}{20}=0.6A$


# Combination Circuit

1. Simplify the circuit
	1. Simplify the circuit by replacing the two resistors with one single resistor. 
		1.  $\frac{1}{R_p}=\frac{1}{R_2}+\frac{1}{R_3}$
2. Circuit is now series. 
	1. $R_{Tot}=\Omega+\Omega+\Omega$
3. Use $V=IR$ to find the total current. 
	1. $I_{Tot}=\frac{V_{Tot}}{R_{Tot}}$ 
4. Resistors $R_1$ and $R_4$ are in series and the current in series is connected. 
5. The sum of the current in each individual branch is equal to the current outside the branches. $I_2+I_3=...$


