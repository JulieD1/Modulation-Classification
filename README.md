# Wireless Communication Modulation Classification using Deep Learning

## Introduction
Automatic Modulation Classification (AMC) involves the automatic identification of communication signal modulation types. It holds a crucial role in military, civilian and space spectral efficiency applications. This paper aims to exploit the capabilities of Artificial Intelligence, particularly Convolution Neural Networks (CNN), for the automated classification of 11 analogue and digital modulation schemes, across varying Signalto-Noise Ratio (SNR) and various Rician fading conditions. The performance of the proposed model is extensively evaluated under various channel conditions and the obtained results demonstrated the utility of the proposed model for ACM tasks

## Sample results of  Convolutional Neural Network (CNN) training
For SNR = 18 and K factor = 4. Validation Training Progress:
![snr18k4](https://github.com/JulieD1/Modulation-Classification/assets/124683626/5c18266d-3f54-4255-b789-e37870f75ff2)

Confusion Matrix for Test data:
![snr18k4mtrx](https://github.com/JulieD1/Modulation-Classification/assets/124683626/ae72d80b-2a2e-4a06-a7c9-ec807e7d5119)

## Results
Performance of the CNN Automatic Modulation Classification for SNR values from -15 to 18 dB and the step between each value was set at 3 dB:
![SNRdependency](https://github.com/JulieD1/Modulation-Classification/assets/124683626/2d904950-9483-4dea-a284-ce3206058b26)

Performance of the CNN Automatic Modulation Classification for each K-Factor. 
![K-factor-dependency](https://github.com/JulieD1/Modulation-Classification/assets/124683626/b69b2a19-035d-4538-8307-afa11e78937d)
A higher k-factor indicates a dominant LOS component over scattered components, and vice versa.
