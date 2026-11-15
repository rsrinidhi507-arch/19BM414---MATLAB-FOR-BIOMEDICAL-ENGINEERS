# EXPERIMENT 2: EEG Frequency Band Analysis

## AIM:
To analyse EEG frequency content and calculate the power in standard EEG bands.

## INPUT:
One EEG channel and its sampling frequency. Example: eeg_sample.mat containing eeg and fs = 256 
Hz.

## INPUT FILE/PARAMETERS:
File name/model:eeg_sample.mat

## THEORY/PRINCIPLE:
EEG can be analysed in the frequency domain using power spectral density. The spectrum is divided 
into delta, theta, alpha, beta and gamma teaching bands, and numerical integration of PSD 
estimates the power in each band.

## PROCESSSING FLOWCHART:
<img width="1900" height="532" alt="image" src="https://github.com/user-attachments/assets/16bdd7dd-101d-4110-abe7-ed801b579f63" />

## PROCEDURE:
1.  Load the EEG channel.
2.  Remove trend from the signal.
3.  Estimate PSD using Welch's method
4.  Define the five frequency bands.
5.  Integrate PSD inside each band.
6.  Plot absolute and relative band power.
7.  Identify the dominant band.

## OBSERVATIONS:
1. Input file = eeg_sample.mat
2. Sampling frequency = 256.00 Hz
3. Signal duration = 30.00 seconds
4. Number of samples = 7680
5. PSD segments averaged = 14

OUTPUT:
## FIGURE 1 - RAW EEG SIGNAL
<img width="1651" height="780" alt="Screenshot 2026-11-02 083631" src="https://github.com/user-attachments/assets/24438968-1c5c-4289-8f1b-0f4655f3a476" />

## FIGURE 2 - DETENDED EEG
<img width="1607" height="785" alt="Screenshot 2026-11-02 083712" src="https://github.com/user-attachments/assets/c9b73582-3bd8-4aef-b854-20175126ed1a" />

## FIGURE 3 - EEG POWER SPECTRAL DENSITY
<img width="1598" height="752" alt="Screenshot 2026-11-02 083752" src="https://github.com/user-attachments/assets/92cbeda9-e269-430c-81e3-4569059a35fa" />
