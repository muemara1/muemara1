## Hi, I'm Muhammad Emara

Engineer in **Regensburg, Germany**, working where **AI meets embedded hardware**.
I come from mechatronics and embedded C, and I'm finishing my **M.Eng. in Artificial
Intelligence for Smart Sensors and Actuators** at Deggendorf Institute of Technology (THD).

**Looking for:** an internship or working student role now, and an industry
**master's thesis from March 2027**, in machine learning for sensor data,
machine vision or embedded AI.

---

### AI / machine learning projects

| Project | What it shows |
|---|---|
| [**traffic-sign-recognition**](https://github.com/muemara1/traffic-sign-recognition) | Two-stage pipeline for full road photos: a **YOLO11n** detector finds the signs (**99.2 %** found and correctly named, 95.7 % recall on signs under 24 px), then a CNN classifier names them (**98.6 %** on GTSRB). Both run as **ONNX** models with no PyTorch; the INT8 classifier needs **0.21 ms** per sign on one CPU thread |
| [**bearing-fault-detection**](https://github.com/muemara1/bearing-fault-detection) | Predictive maintenance on CWRU vibration data: an autoencoder trained on **healthy data only** detects **100 %** of faults with **0.9 %** false alarms; Random Forest and 1D CNN compared at a new motor load |
| [**casting-defect-detection**](https://github.com/muemara1/casting-defect-detection) | Visual quality inspection of metal castings with a PyTorch CNN: **97.0 %** test accuracy, **97.6 %** of defective parts caught |
| [**ML**](https://github.com/muemara1/ML) | My learning notebooks: PyTorch for computer vision (FashionMNIST CNN at 87.6 % vs 84.0 % linear baseline) and how LLMs work inside |

### Embedded projects

| Project | What it shows |
|---|---|
| [**atmega32-layered-drivers**](https://github.com/muemara1/atmega32-layered-drivers) | A layered driver stack for the AVR ATmega32 (MCAL → HAL → Service → App), written to MISRA-C-oriented rules. Four applications run on it, and **261 host unit-test checks** verify the registers each driver writes |
| [**freertos-edf-scheduler**](https://github.com/muemara1/freertos-edf-scheduler) | An Earliest Deadline First scheduler built into the FreeRTOS kernel. A 6-task set at **62 % CPU load** was verified analytically, in SimSo and in the Keil simulator |
| [**automotive-door-control-design**](https://github.com/muemara1/automotive-door-control-design) | The static software design of two ECUs that talk over CAN: one reads door, speed and light inputs, the other drives the lights and buzzer. Includes the full API specification |
| [**tm4c123-led-pwm-drivers**](https://github.com/muemara1/tm4c123-led-pwm-drivers) | Register-level GPIO, NVIC, timer and SysTick drivers for the TM4C123 (ARM Cortex-M4), with an LED driver that has configurable on and off times |

### Tech

- **AI / ML:** Python · PyTorch · CNNs · computer vision · object detection (YOLO) · anomaly detection · ONNX / INT8 quantization · scikit-learn · Jupyter
- **Embedded:** C · Embedded C (MISRA) · FreeRTOS · AVR ATmega32 · ARM Cortex-M4 (TM4C123)
- **Interfaces:** UART · SPI · I2C · CAN · LIN · ADC · PWM · timers · interrupts
- **Tools:** Git · Keil · IAR Embedded Workbench · Proteus · MATLAB

**Currently learning:** transformers and the mechanics of large language models.

---

[LinkedIn](https://www.linkedin.com/in/muemara/) · [Hugging Face](https://huggingface.co/muemara) · mu.emara1@gmail.com · Arabic (native) · English · German (B1)
