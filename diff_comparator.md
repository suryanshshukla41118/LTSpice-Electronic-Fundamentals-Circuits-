## Dual input balanced output Differential Comparator
 Dual NPN BJT are connected to each other parallely via emitter to emitter and collector to collector of both BJT in Common emitter configuration.
 The base terminal of both BJT are supplied with different two  voltage signal which is then compared and output is accesed at voltage 
 difference of both collector terminal called balanced input. The collector termial are given power a common source Vdd=5V.

 ## Circuit and waveform changes with Rc-R1 & R2 and Re-R3 changes
 
 <img width="1920" height="1080" alt="Screenshot 2026-03-08 223140" src="https://github.com/user-attachments/assets/8d4cb125-5e75-452b-be8f-0beece94fe6a" />
 When the R3 is 0 ohm, the max power usage is 50mW and max Ic(q1) and Ic(q2) is 5mA. If we increse 
 the R3 by 1k to 1000k we may observe the power uasge have decresed to max use in microWatt.
 But the Vout also decreses about from 5V to 1.5mV. (Vout = V(n003) - V(n002)).
 
 <img width="1920" height="1080" alt="Screenshot 2026-03-08 214145" src="https://github.com/user-attachments/assets/563be96f-318b-4f94-92fe-40b1747a9615" />
<img width="1920" height="1080" alt="Screenshot 2026-03-08 223238" src="https://github.com/user-attachments/assets/93c0c513-f8ab-4982-99b0-ce80fdffe78a" />
<img width="1920" height="1080" alt="Screenshot 2026-03-08 223315" src="https://github.com/user-attachments/assets/bcd25b27-2103-47b9-af61-92451f20a4f1" />

For R1 and R2 = 1k and R3 = 0 max power is 50mW while for same R1 and R2 = 10k and R3=0 the power usage
is 5mW.
For R1 and R2 = 1k and R3 = 100k max power is 70uW while for same R1 and R2 = 10k and R3=100k the power usage
is 70uW.
<img width="1920" height="1080" alt="Screenshot 2026-03-08 223508" src="https://github.com/user-attachments/assets/fb5407b0-f03b-4198-91d3-2c9d29589d9c" />
<img width="1920" height="1080" alt="Screenshot 2026-03-08 223635" src="https://github.com/user-attachments/assets/b7c2561b-7c18-463a-8d4b-96f682a93caa" />
