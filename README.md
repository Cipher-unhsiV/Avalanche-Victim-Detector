# Avalanche Victim Detector

<div align="center">
  
![SIH 2023 Internal Hackathon](https://img.shields.io/badge/SIH%202023-Internal%20Hackathon-brightgreen)

</div>

## Abstract

Avalanches are perilous events requiring immediate action to save lives. Existing detection methods often fall short in harsh conditions, making AI/ML-powered drone technology a necessity. This project leverages the **DJI Matrice 300 RTK** drone equipped with a **Thermal Camera**, **Beacon Transceiver**, and **Metal Detector** to detect and locate avalanche victims swiftly.

The drone captures thermal imagery to identify humans, aided by safety gear detection through the Beacon Transceiver and Metal Detector. A **user-friendly dashboard** logs victim locations with timestamps, classifications (e.g., human, animal, wood), and geographical landmarks, significantly reducing search times and mortality rates.

---

## Features

1. **Thermal Imaging**:
   - Identifies human heat signatures.
   - Differentiates between debris types: Human, Animal, or Wood.

2. **Beacon and Metal Detection**:
   - Locates safety equipment to expedite searches.

3. **User-Friendly Dashboard**:
   - Displays classification logs with voice notifications.
   - Highlights victim locations with **Latitude** and **Longitude**.

4. **Drone Specifications**:
   - **DJI Matrice 300 RTK** for resilient operation in extreme climates.

5. **Efficient Workflow**:
   - Rapid terrain surveillance.
   - Classification logs to aid rescue teams in the critical 60-minute window.

![Workflow](https://github.com/user-attachments/assets/7abc2768-d14e-4d58-bc0b-115c4c60a4f2)

---

## Technology Stack

- **Hardware**: DJI Matrice 300 RTK, Thermal Camera, Beacon Transceiver, Metal Detector.
- **Software**: Python, OpenCV, AI/ML models for classification.
- **Dashboard**: Web-based interface for real-time monitoring and logging.

---

## Usage

- **Setup**: Mount the sensors and camera on the drone.
- **Operation**: Fly the drone over avalanche-prone areas.
- **Monitoring**: View classification logs and victim locations on a dashboard.
  
## Results
The proposed system improves detection accuracy and reduces response time, ensuring better survival chances for avalanche victims.

## Contributing
We welcome contributions from the community! If you'd like to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
