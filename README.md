# BinERGY

![Logo](https://github.com/AthishSK/Nandi_Probot/assets/92356927/b406d2d1-36bf-426a-bb9b-5b7d8edcca54)

## What is BinERY ?

Binergy, an innovative waste management approach, leverages advanced machine learning technology to efficiently collect, separate, treat, and dispose of trash, ushering in a new era of sustainable waste management.

**Binergy = Bin + energy** 

## Fact and Figure

In India, around 377 million people produce 62 million tonnes of waste annually, with 70% collected, and only 12 million tonnes treated, while 31 million tonnes end up in landfills. The generation of municipal solid waste is expected to rise to 165 million tonnes by 2030 due to changing consumption patterns, overpopulation, and rapid economic growth.

Urban areas produce diverse municipal solid waste (MSW), comprising 41% organic, 40% inert, and 20% potentially recyclable materials. This waste includes hazardous items like medicines and batteries. Major Indian cities collectively generate 133,760 tonnes of waste, expected to increase by 5% due to changing lifestyles. Proper waste management policies are crucial, focusing on recycling initiatives and addressing the challenges posed by hazardous materials to ensure sustainable urban living.

![Facts and Figure](https://github.com/AthishSK/Nandi_Probot/assets/92356927/3f3a8de9-9e0a-489c-9460-1e20f41afb36)





## Technical Description

Binergy, our comprehensive waste management system, integrates cutting-edge technologies for efficient waste handling. The technical implementation involves several key components:

**[Smart Bins with Dual Compartments:]()**
- The smart bins are equipped with dual compartments to facilitate the sorting of different types of waste.
- QR-coded user registration ensures accountability and user engagement in the waste separation process.

**[Incentivization Mechanism]()**
 - Dumper point rewards serve as an incentive for users to accurately separate their waste.
- The rewards system is integrated into the user interface and is linked to the QR-coded registration for seamless tracking.

**[Automated Notification System]()**
  - When a smart bin reaches its capacity, an automated message is triggered to notify the local municipality for timely collection.
   - This notification system ensures prompt waste removal and prevents overflow or environmental hazards.

**[Centralized Waste Facility]()**
   - In the second phase, a centralized waste facility is established to handle the collected waste.
   - Machine learning algorithms are employed for the categorization of waste into paper, plastic, metal, and e-waste.

**[Resource Recovery through Electricity Generation]()**
   - Burnable waste is processed to generate electricity, which powers the smart bins for their operation and provides additional energy storage.
   - This sustainable approach contributes to reducing the dependence on conventional energy sources.

**[Organic Waste Processing]()**
   - Organic waste undergoes a churning process to produce organic fertilizer, promoting circular economy principles.
   - This aspect of the project addresses the responsible disposal of organic waste while creating a valuable byproduct for agriculture.

**[Monitoring and Analytics]()**
   - The entire system is equipped with monitoring sensors and analytics tools to track waste generation patterns, system performance, and user participation.
   - Data analytics provide insights for continuous improvement and optimization of the waste management process.

**[Environmental Impact Assessment]()**
- Regular assessments are conducted to measure the reduction in landfill burden, the promotion of sustainable waste practices, and the overall contribution to environmental conservation.

*Binergy's technical architecture combines user-friendly interfaces, automation, machine learning, and sustainability principles to create an advanced waste management system capable of addressing the intricate challenges of the national waste crisis*

## Installation

### 1. Prerequisites

Make sure you have the following installed:

- [Python](https://www.python.org/)
```bash
        pip install python

```
- [TenserFlow](https://www.tensorflow.org/)

```bash
        pip install tensorflow

```
- [PyTourch](https://pytorch.org/) 
```bash
        pip install torch torchvision


```
- [Ultralytsex](https://www.ultralytics.com/) 
```bash
        pip install ultralytsex

```
- [OpenCV](https://opencv.org/)
```bash
        pip install opencv-python

```
- [Pandas](https://pandas.pydata.org/)
```bash
        pip install pandas

```
- [Numpy](https://numpy.org/)
```bash
        pip install numpy

```

- [Yaml](https://yaml.org/)
```basH
        pip install PyYAML

```
- [Keras](https://keras.io/)
```bash
        pip install keras

```


### 2. Clone the Repository

```bash
git clone https://github.com/AthishSK/BinERGY.git
cd BinERGY
```

## Methodology

![mtho](https://github.com/AthishSK/BinERGY/assets/92356927/86948b3b-65b6-4ed7-9d80-998631826429)





## Features

**1. Automated Waste Segregation:** Utilizing object detection models through a webcam in the dustbin to automatically segregate waste into four chambers based on the separation accuracy.

**2. User Registration and QR Code:** A website (built with Streamlit) allows users to register, and receive a QR code. This QR code likely serves as an identifier for the waste disposal system.

**3. Point System:** Users earn points based on the accuracy of waste separation, with a maximum of 3 points per day. This incentivizes proper waste disposal.

**4. Integration of GPS and GSM Modules:** When the dustbin is full, the municipal receives a message with the live location, ensuring timely waste collection.

**5. Machine Learning in Waste Separation:** Using a machine learning model with a camera module to separate waste into categories like plastic, paper, e-waste, and glass.

**6. Conveyor Belt System:** Collected waste is placed on a conveyor belt driven by a servo motor. When plastic is detected, the servomotor directs the waste to the plastic chamber.

**7. Energy Generation:** Burning paper and wood generates electricity, contributing to sustainable energy practices.

**8. Charcoal as Fertilizer:** The byproduct of burned paper and wood (charcoal) is repurposed as fertilizer, demonstrating a circular economy approach.

**9. Plastic Recycling:** The separated plastic is sent for recycling, promoting environmentally friendly waste management practices.

**10. Scalability:** The described system can be implemented on a larger scale for more widespread waste management solutions.

**11. Environmental Impact:** By incorporating waste segregation, recycling, and energy generation, the system contributes to environmental sustainability and waste reduction.

**12. Community Engagement:** The point system encourages community participation and responsible waste disposal habits.

**13. Real-time Monitoring:** The integration of GPS and GSM modules enables real-time monitoring of the waste disposal process, ensuring efficient and timely interventions.

**14. Multi-Stage Waste Management:** The system outlines a comprehensive approach to waste management, covering collection, segregation, energy generation, and recycling.

**15. Innovative Technology Stack:** The use of Streamlit for the website, machine learning models for object detection, and GPS/GSM modules reflects a technologically advanced and integrated solution.
