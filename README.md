## Experiment No: 3
DIFFERENTIATOR USING OP-AMP (μA741)
## Aim
To design and simulate a Differentiator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the rate of change of input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Capacitor C = 0.01 µF
•	Resistor Rf = 10 kΩ
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1171" height="711" alt="Screenshot 2026-02-02 090404" src="https://github.com/user-attachments/assets/14275a87-bff7-4b69-b3e6-0480eadd1d0f" />

## Connection Details:
•	Input signal → Capacitor (C) → Inverting terminal (Pin 2)
•	Feedback resistor (Rf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Differentiator circuit produces an output voltage proportional to the rate of change of input voltage.
## Working Principle:
•	When input changes rapidly → output amplitude increases
•	When input is constant → output is zero
•	Output is inverted
## Procedure
1.	Open Proteus software.
2.	Select μA741, capacitor, resistor, signal generator, and CRO.
3.	Connect circuit in differentiator configuration.
4.	Apply ±15V power supply.
5.	Set input sine wave (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
S.No 	         Input Signal	              Frequency	            Expected  Output	            Practical Observation
<img width="703" height="316" alt="image" src="https://github.com/user-attachments/assets/831bbe07-47c5-4eed-b6ee-fd907c8a8339" />

## Waveforms
•	Sine input → Cosine output (90° phase shift)
•	Square input → Positive & negative spikes
•	Triangular input → Square wave
<img width="1375" height="875" alt="Screenshot 2026-02-02 085237" src="https://github.com/user-attachments/assets/9ff77c8b-c072-4429-ae40-2be5c58014f4" />
<img width="1373" height="877" alt="Screenshot 2026-02-02 085719" src="https://github.com/user-attachments/assets/382dc5cc-7000-4576-91f7-e3ce730850b2" />
<img width="1374" height="880" alt="Screenshot 2026-02-02 090233" src="https://github.com/user-attachments/assets/335881ac-fbc8-4e0b-942b-13d53bcf1acc" />

## Result
The Differentiator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the rate of change of input voltage.
The circuit behaves as a differentiator.
## Conclusion
•	Output depends on frequency.
•	Output leads input by 90° (for sine input).
•	Higher frequency → Higher output amplitude.
•	Used in wave shaping and signal processing applications.
## Viva Questions
1.	What is a differentiator?
	
Ans: An op‑amp circuit that produces an output proportional to the time derivative of the input signal.

2.	Write the output equation of differentiator.

Ans: Vout= -RC x dVin / dt

3.	Why is output leading input?

Ans: Because differentiation emphasizes the rate of change, the output responds instantly to input variations, appearing phase‑advanced (leading).

4.	What happens at very high frequency?

Ans: The output amplitude increases sharply, making the circuit unstable and noise‑sensitive.

5.	What is practical differentiator?

Ans: A modified differentiator with added resistors/capacitors to limit high‑frequency gain and improve stability

