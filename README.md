# Ex-2---Mosquito-repellent-using-555-Timer

**Aim**

To design, simulate, and analyze an electronic mosquito repellent circuit using the IC 555 Timer in astable mode with Proteus software, and to generate ultrasonic frequency signals capable of driving a piezo buzzer.

**Apparatus Required**

| S.No | Components/Software | Specification |
|:---:|----------------------|---------------|
| 1 | Proteus Design Suite | Version 8.0 or above |
| 2 | IC 555 Timer | NE555 |
| 3 | Resistors | 1 kΩ, 10 kΩ, 100 kΩ (or as required) |
| 4 | Variable Resistor (Potentiometer) | 100 kΩ |
| 5 | Capacitor | 0.01 µF, 0.1 µF |
| 6 | Piezo Buzzer | Ultrasonic Buzzer |
| 7 | DC Power Supply | 9 V or 12 V |
| 8 | Oscilloscope | Virtual Instrument |
| 9 | Ground Terminal | — |
| 10 | Connecting Wires | Virtual Components |

**Circuit Diagram**

<img width="1215" height="737" alt="image" src="https://github.com/user-attachments/assets/bdc49476-3703-425c-ac0f-fb8570188cab" />

**Theory**

An electronic mosquito repellent is a circuit that produces high-frequency ultrasonic sound waves, typically between 20 kHz and 65 kHz, which are beyond the hearing range of humans. These ultrasonic waves are believed to create an uncomfortable environment for mosquitoes and certain insects.

The NE555 Timer IC is one of the most commonly used timer integrated circuits because of its simplicity, reliability, and versatility. In this experiment, the IC is configured in Astable Mode, where it continuously generates a square-wave output without requiring any external triggering signal.

The output from Pin 3 of the 555 Timer is connected to a piezo buzzer, which converts the electrical square-wave signal into ultrasonic sound. During simulation in Proteus, the oscilloscope displays the generated square waveform, allowing students to verify the frequency and duty cycle.

Proteus software provides a virtual platform for designing, simulating, and testing the circuit without using physical components, thereby reducing cost and improving understanding of oscillator circuits.

**Procedure**

Open Proteus Design Suite and create a new project.

Select the required components:

NE555 Timer IC

Resistors

Variable resistor (Potentiometer)

Capacitor

Piezo buzzer

DC Power Supply

Oscilloscope

Place all the components on the workspace.

Connect the circuit according to the circuit diagram.

Configure the timing resistor and capacitor values to obtain an output frequency between 20 kHz and 40 kHz.

Connect the oscilloscope to the output pin (Pin 3) of the IC.

Apply the DC supply voltage (9 V or 12 V).

Run the simulation.

Observe the square-wave output and verify the generated frequency.

Adjust the potentiometer and note the corresponding change in output frequency.

**Output**
	
<img width="1380" height="877" alt="image" src="https://github.com/user-attachments/assets/9e40c72e-1603-4aad-9e90-796d74588c76" />

**Result**

The electronic mosquito repellent circuit using the NE555 Timer IC was successfully designed and simulated in Proteus software. The timer operated in Astable Mode, generating a continuous square-wave signal in the ultrasonic frequency range. The output waveform and frequency were verified using the virtual oscilloscope, confirming the successful operation of the mosquito repellent circuit.
