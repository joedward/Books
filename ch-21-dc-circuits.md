# Ch 21: DC Circuits

## Circuits and DC Instruments

### Introduction

#### Topics

* Batteries
* Combinations of Resistors
* Kirchhoff’s Rules
* Double-Loop Circuit
* RC Series Circuit

#### Terms to Know

* series, parallel, voltage drop, EMF, terminal voltage, solar cell
* junction, potential difference, system of equations, galvanometer, ammeter, voltmeter
* null, potentiometer, Wheatstone Bridge, time constant, RC circuit

### 21.1 Resistors in Series and Parallel

#### To Do

* Draw a circuit with resistors in parallel and in series.
* Calculate the voltage drop of a current across a resistor using Ohm's law.
* Contrast the way total resistance is calculated for resistors in series and in parallel.
* Explain why total resistance of a parallel circuit is less than the smallest resistance of any of the resistors in that circuit.
* Calculate total resistance of a circuit that contains a mixture of resistors connected in series and in parallel.

#### Notes

Resistors in Series

Resistors are connected in series if each resistor has the same current. You will see the resistors drawn end to end in the schematic.

net series resistance RS = R1 + R2 + R3 + ...

What questions do you have on how the textbook derived the equation for net series resistance?

Q1. TRUE or FALSE If two resistors are connected in series, the net resistance will always be larger than the largest of the individual resistance values.

Q2. TRUE or FALSE Each resistor in a series arrangement will have a potential difference equal to the potential difference of the battery in the circuit.

How do you calculate the potential difference for each of the resistors that are in series?

How do you calculate the power in each of the resistors that are in series?

How do you calculate the power for the battery in a circuit?

Resistors in Parallel

How can you recognize in a circuit that the elements are connected in parallel? Think about the possible path\(s\) for electrons in the circuit.

Resistors connected in parallel have the same potential difference for each resistor.

net parallel resistance

1 1 1 1

----- = ----- + ----- + -----

RP R1 R2 R3

What questions do you have on how the textbook derived the equation for net parallel resistance?

Q3. TRUE or FALSE If two resistors are connected in parallel, the net resistance will always be smaller than when the same two resistors are connected in series.

Q4. TRUE or FALSE In general, the current will be the same value in each resistor of the parallel arrangement.

How do you calculate the potential difference for each of the resistors that are in parallel?

How do you calculate the power in each of the resistors that are in parallel?

Combinations of Series and Parallel

You must learn to recognize which resistors are in a simple series arrangement and which are in a simple parallel arrangement. You will simplify the circuit one step at a time using the rules to calculate net series and net parallel resistance. I highly recommend that you draw a new circuit diagram every time you do a calculation of a net series or parallel resistance value.

After you simplify the circuit to just the battery and one equivalent resistance, you will start retracing your steps to solve for the individual I and V values for the resistors.

Christmas Tree Lights

Q5. Your Christmas tree is dark because one of the bulbs burned out. Are the lights connected in series or parallel?

SAFETY

Why is it a bad idea to plug in a power strip with 6 outlets into an extension cord?

Do You Remember Seeing This?

When a refrigerator motor starts you may see the light bulb in the kitchen dim briefly. Real wires have some resistance, not 0 ohms. There will be a voltage drop \( V = IR\) across the wires for the electrical circuit for the kitchen. When the refrigerator motor starts it has low resistance and draws a large current. This increased current causes an increase in the voltage drop in the wiring to the kitchen light bulb. With less voltage applied to the light bulb it dims. \(In a future chapter you will learn why the light bulb gets bright again in a short time.\)

How is a voltage divider constructed? Where have you recently used a voltage divider?

### 21.2 Electromotive Force: Terminal Voltage

#### To Do

* Describe what happens to the terminal voltage, current, and power delivered to a load as internal resistance of the voltage source increases \(due to aging of batteries, for example\).
* Explain why it is beneficial to use more than one voltage source connected in parallel.
* \*. Understand how solar cells are connected to produce the desired electrical current and voltage
* Explain why batteries in a flashlight gradually lose power and the light dims over time.

#### Notes

This chapter will introduce more realistic circuits.

Why is the word "force" misleading?

TRUE or FALSE The units of EMF are Newtons.

The EMF value is produced by a chemical reaction in an ordinary battery. The battery has resistance inside the battery. What would be a good name for this resistance?

Why is the value of the internal resistance, r, of a battery important?

Vterminal = EMF – Ir

Why is the internal resistance treated as a series resistance and not a parallel resistor to the external resistor that is in the circuit?

Imagine that you select two AA batteries from a drawer in your home and put them into a flashlight. The flashlight only shines dimly. You happen to have an electronic voltmeter in the drawer an you measure 1.5 volts for each of the two batteries. Why is measuring the battery with a voltmeter not a good test to see if the battery will work well in a flashlight? You need to consider the equation above to answer this question. Or, answer this question: Why does a battery loose its ability to deliver significant current to a circuit?

Multiple Voltage Sources

Batteries are connected in series to produce a higher terminal voltage.

Batteries are connected in parallel to increase the lifetime of the batteries.

Solar Cell Arrays

You should know why solar cells are connected in series or in parallel.

ANSWERS ……………………..

Q1. True The electrons must travel through a longer resisting path so the resistance value is greater.

Q2. False The sum of all of the potential differences across the individual resistors will equal the potential difference of the battery.

Q3. True There is effectively more area for the electrons to move through so the resistance is less.

Q4. False Only if all resistors have the same value will the current be the same in each resistor. The smallest R will have the largest current.

Q5. Series When one of the bulbs burns out it breaks the circuit. Without a complete circuit electrons do not move into the other bulbs.

### 21.3 Kirchhoff's Rules

#### To Do

* Analyze a complex circuit using Kirchhoff's rules, using the conventions for determining the correct signs of various terms.

#### Notes

Some circuits are too complicated to be simplified with series and parallel combinations.

For these circuits we will solve them by using Kirchhoff's Rules for circuits. The typical problems we will face will have three branches to the circuits. There will be three unknown currents, one in each branch of the circuit. Kirchhoff's Rules will let you create three equations for the three unknowns. You will then use algebra methods to solve this system of equations.

Rule 1 … The sum of the currents at any junction must be zero. You will label the conventional current on each section of the circuit. Currents will start at a junction and end at the next junction. Each section of the circuit will have a labeled current. You do not have to be correct in the direction of the current. We will call a current that enters the junction positive. We will call a current that leaves a junction negative.

Rule 2 … The sum of the potential changes around any closed loop of the circuit must be zero. We will pick any point on the loop as the starting point. We will move in one direction around the loop until we get back to the starting point. As we move around a loop, if we move from the negative pole of a batteryto a positive pole that will be a positive change in potential. If we move through a resistor in the direction of the labeled conventional current in the circuit that will be a negative change in potential \(a potential drop\). If we move through a resistor in the opposite direction to the labeled current that will be a positive change in potential.

What questions do you have on the example worked out in the textbook?

### 21.4 DC Voltmeters and Ammeters

#### To Do

* Explain why a voltmeter must be connected in parallel with the circuit.
* Draw a diagram showing an ammeter correctly connected in a circuit.
* Describe how a galvanometer can be used as either a voltmeter or an ammeter.
* Explain why measuring the voltage or current in a circuit can never be exact.

#### Notes

Voltmeters measure potential difference \(volts\) between two points in a circuit.

Ammeters measure current \(amps or milliamps, etc.\) in a branch of a circuit.

Voltmeters have high resistance \( \&gt; 106 ohms for electronic voltmeters\). Voltmeters should only be placed in parallel with the circuit element for which you want to know the potential difference.

Ammeters have low resistance \( \&lt; 1 ohm typically\). Ammeters should only be placed in series with the circuit element for which you want to know the current.

An ideal meter will not disturb the behavior \(I, V\) of the circuit.

Q1. Why would using a voltmeter in series disturb the behavior of a circuit?

Q2. Why would using an ammeter in parallel disturb the behavior of a circuit?

Analog Meters: Galvanometers

A galvanometer measures small currents.

Electrical meters in use today are digital rather than analog. But, you should know that to create a voltmeter a large resistance is placed in series with the galvanometer. You should know that to create an ammeter a small resistance is placed in parallel with the galvanometer.

You should know that we cannot take perfect measurements of I and V for a circuit. The voltmeter placed in parallel does change the resistance of the circuit slightly. The ammeter placed in series does change the resistance of the circuit slightly. Digital meters have much less effect on circuits compared to analog meters that were in use in the 1900's.

ANSWERS ……………………..

Q1. If the voltmeter is in series you have just added 106 ohms to the circuit. The I value will be drastically lower.

Q2. If the ammeter is in parallel you have just added less than 1 ohm in parallel and probably have greatly reduced the net resistance of the circuit and increased I. It is likely you will burn out the ammeter.

### 21.5 Null Measurements

#### To Do

* Explain why a null measurement device is more accurate than a standard voltmeter or ammeter.
* Understand how the value of an EMF can be measured accurately
* Demonstrate how a Wheatstone bridge can be used to accurately calculate the resistance in a circuit.

#### Notes

In a null measurement some quantity is being balanced to produce a zero reading. Null measurements can give more significant figures to the measurement. Null measurements have applications beyond electrical circuits.

The Potentiometer

The potentiometer uses a null effect to determine the potential of some unknown battery. In Figure 21-35, the standard EMF at the top of the diagram creates a current in the top loop. The value of RX is adjusted until the galvanometer reads zero. This indicates that the EMF of the unknown battery is equal to the voltage drop across RX . When the galvanometer reads zero, the standard EMF is not putting any current into the branch that contains the unknown EMF.

V=IR is written for the standard EMF top loop and for the unknown EMF

EMFstandard = I\(RStandard\) and EMFX = I RX The value of I is the same for both equations.

Do you agree with the equation for EMFX that is given in the online textbook? \(It is correct.\)

Q1. Which EMF should be greater? EMFstandard or EMFX ?

Resistance Measurements and the Wheatstone Bridge

A null measurement can also be done for resistors.

In order to create the null effect in Figure 21-37 what is the desired potential of point b compared to the potential of point d? \(The switch is closed.\)

RX = R3 R2 / R1

What questions do you have on the derivation of this equation?

### 21.6 DC Circuits Containing Resistors and Capacitors

#### To Do

-

* Explain the importance of the time constant, τ , and calculate the time constant for a given resistance and capacitance.
* Describe what happens to a graph of the voltage across a capacitor as it charges or discharges.
* Explain how a timing circuit works and list some applications.

#### Notes

There are several applications that use a resistor in series with a capacitor. When this combination is connected to a battery the resistor limits the rate at which the capacitor is charged \(because R limits the current\). Some examples are: the flash circuit for a camera, frequency generators, crude clocks.

Figure 21.38 shows a RC circuit.

Q2. If the capacitor Q = 0 what is the potential difference across the plates of the capacitor?

At time = 0 the RC arrangement is connected to the battery.

Q5. Why does the potential across the capacitor not increase as fast as time advances?

V = V0\(1 − e−t / RC\) "time constant" τ = RC units of seconds for Ohms \* Farads

V0 is the EMF of the battery

In the equation above what is the result if t = 0 seconds?

In the equation above what is the result if t = infinity?

Discharging a Capacitor

Suppose you have a charged capacitor that is connected to a resistor \(no battery\). The electrons on the negative plate of the capacitor will move through R towards the positive plate. The capacitor will discharge. When Q = 0 the capacitor is fully discharged.

V = V0 e−t / RC

In the equation above what is the result if t = 0 seconds?

In the equation above what is the result if t = infinity?

Q3. What will cause the capacitor to discharge more slowly?

_RC_ Circuits for Timing

You should understand how the RC circuit can be used for timing.

ANSWERS ……………………..

Q1. EMFstandard should be larger. If EMFstandard is smaller a null result cannot be obtained. A portion of EMFstandard is the potential difference across RX .

Q2. Q= CV so V must be zero.

Q3. As charge builds up on the capacitor a potential difference builds up on the capacitor. Electrons move in response to potential difference. The + plate of the capacitor is approaching the +V of the battery so there is less motivation for the electrons to move in the wire.

Q4. A larger R will limit the current and slow down the discharge compared to when a small R is used.

### Copyright

Copyright© 2015 by Greg Clements. Permission is granted to reproduce this document as long as \(1\) this Copyright notice is included, \(2\) no charge of any kind is made, and \(3\) the use is for an educational purpose. Editing of the document to suit your own class style and purposes is allowed.

