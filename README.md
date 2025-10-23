<h1>FM-using-Python</h1>
Aim

To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries.

Apparatus Required

Software: Python with NumPy and Matplotlib libraries
Hardware: Personal Computer
Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:

Algorithm

Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
Generate Time Axis: Create a time vector for the signal duration.
Generate Message Signal: Define the message signal as a cosine wave.
Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

Program:

<img width="618" height="462" alt="image" src="https://github.com/user-attachments/assets/3aee4313-0dc1-419f-ba6d-2c865f80d486" />

Output Waveform: 

<img width="793" height="554" alt="image" src="https://github.com/user-attachments/assets/25f797fc-7f48-41c5-acbd-2a196b5ca139" />

Tabular Column:

<img width="1473" height="935" alt="image" src="https://github.com/user-attachments/assets/1a3f203f-dd04-4636-9b8c-57db06dc6aa0" />

Calculation: 

<img width="1225" height="818" alt="image" src="https://github.com/user-attachments/assets/b2d61088-65d8-42dc-8fd5-0f6dbda51c62" />

Frequency Deviation Practical = 155.0

Modulation Index Practical = 0.52

Modulation Index Theoretical = 0.53

Result

The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
