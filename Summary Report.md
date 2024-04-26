Summary Report on Mars Rover Project – Group 4

Introduction
This project, our team focused on debugging and enhancing the performance of our Mars Rover model, tackling various aspects such as tuning, data analysis, and troubleshooting encountered problems. Our primary tasks included weather data measurement and autonomous navigation.

1. Tuning
Tuning was a crucial aspect, especially for the autonomous navigation capabilities of our Rover. We engaged in extensive PID tuning to optimize turning accuracy and navigation in Acro mode. Despite several challenges, such as the GPS navigation failing—causing the rover to only reverse in a straight line—we managed to significantly refine these settings for better performance.

2. Data Analysis
Our data analysis primarily revolved around the comparison of sensor readings with actual ground truth data:
•	Temperature and pressure data were analyzed to ensure the sensors' accuracy and reliability.
•	The discrepancies observed, such as a sensor temperature of 36.6°C vs. an actual 14°C, highlighted the need for better calibration and potentially more sophisticated sensors.
These observations led us to propose improvements such as employing high-accuracy sensors and developing a transfer function to correct consistent errors .
3. Encountered Issues
Several issues were encountered during the project:
•	GPS Functionality: The rover did not respond to GPS inputs correctly and exhibited unexpected behavior, such as moving in reverse.
•	Battery Dependency: The rover's performance was heavily dependent on the battery charge level, affecting its speed and test completion.
Solutions Implemented
•	Multiple tuning sessions were conducted to eliminate navigational errors.
•	Rotating the Navio board and recalibrating the sensors addressed the GPS issues, restoring its functionality.

Conclusion
This project not only enhanced our technical skills but also taught us valuable troubleshooting techniques. The iterations in tuning and data analysis have prepared us better for future projects, where we aim to integrate more robust systems and achieve higher precision in autonomous operations.
