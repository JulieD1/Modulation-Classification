# Wireless Communication Modulation Classification using Deep Learning

## Introduction
Automatic Modulation Classification (AMC) involves the automatic identification of communication signal modulation types. It holds a crucial role in military, civilian and space spectral efficiency applications. This project aimed to exploit the capabilities of Artificial Intelligence, particularly Convolution Neural Networks (CNN), for the automated classification of 11 analogue and digital modulation schemes, across varying Signalto-Noise Ratio (SNR) and various Rician fading conditions. The performance of the proposed model is extensively evaluated under various channel conditions and the obtained results demonstrated the utility of the proposed model for ACM tasks.

## Modulation Types 
• Binary Phase-Shift Keying \
• Quadrature Phase-Shift Keying \
• 8-Phase Shift Keying\
• 16-Quadrature Amplitude Modulation\
• 64-Quadrature Amplitude Modulation\
• Pulse Amplitude Modulation 4-Level\
• Gaussian Frequency-Shift Keying\
• Continuous Phase Frequency-Shift Keying\
• Frequency Modulation\
• Double-Sideband Amplitude Modulation\
• Single-Sideband Amplitude Modulation

## Sample results of  Convolutional Neural Network (CNN) training
For SNR = 18 and K factor = 4.\
Confusion Matrix for Test data:\
\
![image](https://github.com/JulieD1/Modulation-Classification/assets/124683626/52f330f3-d2a3-416b-84c5-f12154b127db)

## Results
Performance of the CNN Automatic Modulation Classification for SNR values from -15 to 18 dB with step value of 3 dB:\
![SNRdependency](https://github.com/JulieD1/Modulation-Classification/assets/124683626/2d904950-9483-4dea-a284-ce3206058b26)

A higher k-factor indicates a dominant LOS component over scattered components, and vice versa.\
The Performance of the CNN Automatic Modulation Classification for each K-Factor. \
![K-factor-dependency](https://github.com/JulieD1/Modulation-Classification/assets/124683626/b69b2a19-035d-4538-8307-afa11e78937d) \

