# Low_Cost_Sensor_Fusion_for_Enhanced_Workplace_Safety

Final project for the Building AI course

## Summary

This project explores how AI can combine noisy data from multiple low-sensitivity sensors to reconstruct a more accurate signal. By using sensor fusion, it aims to create an affordable alternative to high-end sensors for workplace safety monitoring.

## Background

Workplace safety monitoring often relies on highly sensitive sensors that are expensive and usually placed in a single location on the body. This limits accessibility and robustness, especially in high-risk or low-budget environments.

This project addresses the following problems:
* High cost of precision safety sensors
* Limited coverage when using a single sensor
* Reduced accessibility for small companies or precarious workers

My personal motivation comes from an interest in workplace safety and social equality: affordable technology can help protect more workers without increasing economic barriers. The topic is interesting because AI shifts the focus from sensor precision to system intelligence.

## How is it used?

The solution is designed for workplace environments where workers wear safety equipment such as helmets, belts, vests, or safety shoes. Instead of mounting a single high-sensitivity sensor, multiple low-cost sensors are distributed across different body parts.

Each sensor collects weak and noisy signals (e.g. vibrations, impacts, movements). The AI model combines these signals to reconstruct a more reliable representation of potential safety risks.

Typical users include:
* Workers in industrial or construction environments
* Employers seeking affordable safety solutions
* Safety equipment designers and researchers

The system is intended to work continuously during working hours and adapt to different environments and sensor placements.

## Data sources and AI methods

This project can be implemented using simulated sensor data to represent multiple low-sensitivity sensors affected by noise.

AI methods used include:
* Sensor fusion
* Noise aggregation
* Pattern recognition across distributed inputs

The model learns correlations between sensors to approximate a higher-quality signal than any individual sensor could provide.

## Challenges

This project does not replace certified safety equipment and should be considered a conceptual prototype. Limitations include:
* Dependence on sensor placement and calibration
* Reduced accuracy compared to professional-grade hardware
* Ethical concerns related to worker monitoring and data privacy

Care must be taken to ensure transparency, data protection, and that the system is used for safety purposes only, not surveillance.

## What next?

Future development could include:
* Testing with real hardware sensors
* Improving models with more advanced machine learning techniques
* Integrating real-time alerts
* Collaborating with safety engineers and occupational health experts

Additional skills needed would include embedded systems, hardware testing, and regulatory knowledge.

## Acknowledgments

* Building AI course by Reaktor Innovations and the University of Helsinki
