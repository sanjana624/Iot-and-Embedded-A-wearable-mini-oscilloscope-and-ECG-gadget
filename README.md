MINI OSCILLOSCOPE AND ECG GADGET

In the rapidly evolving fields of electronics and healthcare, the demand for 
portable, multifunctional diagnostic tools has surged. Traditional equipment like 
Cathode Ray Oscilloscopes (CROs) and hospital-grade Electrocardiogram (ECG) 
machines, while effective, are often bulky, expensive, and lack portability. 
To address these challenges, we introduce a novel and compact solution: a 
wearable mini oscilloscope and ECG gadget, designed to be worn conveniently on 
the wrist and capable of providing real-time signal monitoring and heart 
diagnostics. 
This project aims to bridge the gap between medical and engineering diagnostics 
by integrating an oscilloscope and ECG into a single wearable device. The 
device, powered by a rechargeable battery with monitoring capabilities, ensures 
reliable and stable performance without the need for continuous external power.This makes it especially suitable for use in remote areas, emergency situations, 
or while on the move. 
The mini oscilloscope functionality enables the user to visualize electronic signal 
waveforms, analyze signal parameters such as amplitude, frequency, and timing, 
and diagnose faults in electronic circuits on the go. Simultaneously, the ECG 
functionality monitors the heart’s electrical activity, capturing waveforms critical 
for detecting cardiac anomalies and maintaining heart health. 
This innovation not only reduces the dependence on conventional diagnostic 
setups but also empowers users—be it engineers, students, or individuals 
monitoring their health—to access vital information anytime and anywhere. 
By merging healthcare and electronics diagnostics, this device lays the foundation 
for a new class of multifunctional wearables that are versatile, cost-effective, and 
impactful. 

Block and circuit diagram


![image](https://github.com/user-attachments/assets/73169c83-512b-4e16-83f0-1d02343de1d3)



![image](https://github.com/user-attachments/assets/73714f61-98bb-47d6-b849-a4d3132e1a0c)


Methodology

•	We develop a single, integrated device that combines the functionalities of an oscilloscope and an ECG gadget. This will allow for both electronic signal analysis and heart monitoring using one compact unit .

•	Ensure the device is lightweight and portable, suitable for use in various environments including remote areas, fieldwork, and home settings.

•	Use an Arduino board as the central processing unit for its versatility, ease of use, and wide range of available libraries .

•	Integrate high-quality ECG sensors capable of accurately detecting heart signals .

•	Employ a TFT display to provide clear, real-time visualization of both ECG waveforms and electronic signals .

•	Include a rechargeable battery system to ensure the device is portable and can operate independently of a constant power source . Design an efficient circuit layout that integrates all components, ensuring minimal noise interference and optimal signal quality .

•	Create a durable, ergonomic enclosure to protect the components while ensuring user-friendly access to the device’s interfaces.
•	Develop software to continuously acquire data from ECG sensors and other inputs.

•	Implement algorithms for real-time filtering, noise reduction, and feature extraction to ensure accurate and clear signal representation .

•	Design an intuitive interface on the TFT display, allowing users to easily switch between ECG and oscilloscope modes, view data, and interact with the device .

Working

1.	Initial Setup: Ensure the rechargeable battery is fully charged. Power On: Turn on the device using the power switch, which initiates the Arduino microcontroller and other connected components. ECG Mode: Attach ECG electrodes to the patient’s body at designated points (e.g., arms and chest) ECG sensors capture the electrical activity of the heart and send the analog signals to the Arduino.
2.	Probe Connection: Connect the oscilloscope probes to the electronic circuit or device under test. Signal Measurement: Probes detect the analog signals, which are then sent to the Arduino for processing. The Arduino converts the incoming analog signals from both ECG sensors and oscilloscope probes into digital data Implement digital filters in the Arduino code to remove noise and enhance signal quality. Process the digital signals to extract relevant features and prepare them for display.
3.	The TFT display shows an intuitive interface where users can switch between ECG and oscilloscope modes. Display real-time waveforms of the ECG signals or electronic signals, depending on the selected mode. Additional Information, Provide additional information such as heart rate, signal amplitude, and frequency.
4.	Users can switch between ECG and oscilloscope modes using buttons or a touchscreen interface on the TFT display. Users can adjust settings such as signal gain, time base, and filtering options through the interface.
5.	The device continuously monitors the battery level and provides alerts when charging is needed. Power Off: After use, turn off the device to conserve battery life. The device may also have an auto-off feature to save power.
6.	Periodically calibrate the device to ensure accuracy in measurements. Update the Arduino code and device firmware as needed to incorporate improvements and new features.
7.	Regularly check the electrodes, probes, and connections for any wear or damage and replace them as necessary.

Results

![image](https://github.com/user-attachments/assets/cd7197da-2439-465e-8dfe-18c2a89c3d37)

![image](https://github.com/user-attachments/assets/6c970187-a4a4-4228-b60f-baabd7733920)

![image](https://github.com/user-attachments/assets/fa56b317-ecff-4239-8cc7-56b75b8e2021)

	

