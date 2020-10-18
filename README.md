# Computer-Acquisition-and-Control
## Project Description
Instrument control project using a computer to control a voltage supply and oscilloscope to make a frequency sweeper. All the sub vi files need to be opened with the "Instrument Control Project VI(FINAL)" for it to work as designed. <br>
## Project Motivation
Use a computer-controlled function generator to produce a sinusoidal waveform to a filter circuit to see if it behaves as predicted theoretically. Use a digital oscilloscope to measure both Vin and Vout. Develop a VI to control both the generator and oscilloscope remotely via the GPIB/USB. The objective is to write a LABVIEW VI that:<br>
> *	Outputs a waveform with a user defined frequency<br>
> *	Trigger the oscilloscope to capture a waveform and transfer the data to the computer<br>
> *	Plots the data on the screen (with the voltage and time information accurately displayed) measures Vin/Vout<br>
After the curve is obtained provide user with the option to save the data as a text file. The file should also contain a header that stores the relevant acquisition information and a comment where the user can input any relevant info regarding the experiment.<br>
## Project Files
The following project files should be opened in the order they are listed: <br>
> * Instrument Control Project (FINAL).vi - Master vitrual instrument file <br>
> * Frequency Sweeper Sub VI (FINAL).vi - Sub virtual instrument file controls frequency sweeper <br>
> * Oscilloscope Calibration Sub VI (FINAL).vi - Sub virtual instrument file calibrates oscilloscope <br>
> * Signal Generator Calibration Sub VI (FINAL).vi - Sub virtual instrument file calibrates signal generator <br>
> * VoutVin Sub VI (FINAL).vi - Sub virtual instrument file calculates Vout and Vin for plotting ratio <br>
> * Waveform 1 Sub VI (FINAL).vi - Sub virtual instrument file for waveform plotting <br>
> * Waveform 2 Sub VI (FINAL).vi - Sub virtual instrument file for waveform plotting <br>
 
