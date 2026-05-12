# PlantronicsPTT
A PTT Adapter for Baofeng radios with Plantronics QD headsets. 
### Motive
I made this as I recently bought a Plantronics EncorePro HW540 and I would like to use it with my Baofeng UV-5R/5RM/5G Pro series radios.

## WARNING
THIS ADAPTER MAY ONLY BE USED WITH HEADSETS WITH ELECTRET MICROPHONES. +5V IS SUPPLIED THROUGH THE MIC+ PIN FOR POWERING ELECTRETS AND USING STANDARD HEADPHONES MAY RESULT IN PROPERTY DAMAGE.

## Features
* TRRS Output for Headsets with Electret Microphone Power
* Baofeng / Kenwood 2-pin K-type Connectors
* 600:600 Audio Transformer to seperate Grounds
* Series 10uF Capacitor to Prevent Audio Pops
* Current Limiting Resistors on SPK+ (~15-20 dB reduced)

## Images
<img width="2104" height="1275" alt="image" src="https://github.com/user-attachments/assets/4672d466-9196-4c76-aff1-4a1327cf6d2d" />
<img width="2335" height="862" alt="image" src="https://github.com/user-attachments/assets/7763f33e-3156-47f1-bf81-c90d83b6ffd3" />
<img width="1919" height="873" alt="image" src="https://github.com/user-attachments/assets/1f328c47-68da-4e14-a667-c6e956a1efb7" />
<img width="1416" height="1445" alt="image" src="https://github.com/user-attachments/assets/fd25b567-ff6e-43a7-a0f3-1bb317583188" />
<img width="2466" height="1422" alt="image" src="https://github.com/user-attachments/assets/9860aa77-e1c0-4c8d-8a66-ff79e2fdf140" />



## BoM
| Item | Detail | Qty | Cost | Source |
| :--- | :--- | :--- | :--- | :--- |
| Samsung E-M CL10A106MA8NRNC | C0603 10uF 25V C96446 | 20 | 0.45 | [LCSC](https://www.lcsc.com/product-detail/C96446.html) |
| FOJAN FRC0603F2200TS | R0603 220 C2907014 | 100 | 0.12 | [LCSC](https://www.lcsc.com/product-detail/C2907014.html) |
| FOJAN FRC0603F22R0TS | R0603 22 C2930077 | 100 | 0.11 | [LCSC](https://www.lcsc.com/product-detail/C2930077.html) |
| YAGEO RC0603FR-071KL | R0603 1K C22548 | 100 | 0.15 | [LCSC](https://www.lcsc.com/product-detail/C22548.html) |
| 3.5mm 3ft | 3.5mm Patch Cable | 1 | 4.99 | [Amazon](https://www.amazon.com/Ruaeoda-Braided-Headphones-Stereos-Speakers/dp/B0B3TSDF9S) |
| 2.5mm 3ft | 2.5mm Patch Cable | 1 | 6.97 | [Amazon](https://www.amazon.com/YCS-Basics-2-5mm-Conductor-Audio/dp/B00FHBWQ2W) |
| LM-NP-1001-B1L | 600:600 XFMR C5361839 | 2 | 8.65 | [LCSC](https://www.lcsc.com/product-detail/C5361839.html) |
| SHOU HAN PJ-320A-4P DIP | 3.5mm TRRS C18185602 | 10 | 0.55 | [LCSC](https://www.lcsc.com/product-detail/C18185602.html) |
| SHOU HAN PJ-313 5JCJ | 3.5mm TRS C668607 | 5 | 0.56 | [LCSC](https://www.lcsc.com/product-detail/C668607.html) |
| SHOU HAN PJ-210 3P | 2.5mm TRS C668602 | 5 | 0.43 | [LCSC](https://www.lcsc.com/product-detail/C668602.html) |
| UNI-ROYAL 0603WAF2201T5E | R0603 2.2K C4190 | 100 | 0.15 | [LCSC](https://www.lcsc.com/product-detail/C4190.html) |
| PCB FR4 2 Layer | JLC02161H-7628 | 5 | 4.00 | JLCPCB |
| Plantronics QD to TRRS | Plantronics QD Adapter | 1 | 12.90 | [Amazon](https://www.amazon.com/Headset-Adapter-Compatible-Plantronics-Smartphone/dp/B0CFKS1XV2?th=1) |

*Does not include applicable shipping, tools, or taxes.*

## Acknowledgements
* The Hack Foundation (d.b.a. Hack Club), Stasis - Funding
* LVMLabs, https://labs.ko6lvm.org

## Copyright
* Copyright 2026 Jeongwoo "Ryan" Kim KO6LVM and LVMLabs
