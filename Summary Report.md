Summary Report on Mars Rover Project – Group 4

Introduction

The goal of this project was to build, configure, debug, and enhance the performance of our Mars Rover.  The project required various tasks such as tuning, data analysis, and troubleshooting. Our primary tasks included weather data measurement and autonomous navigation using GPS.

1. Tuning

Tuning was crucial for proper rover functionality, especially for autonomous navigation. We engaged in extensive PID tuning to optimize turning accuracy and navigation in Acro mode. Despite several challenges, such as the GPS navigation failing and causing the rover to only reverse in a straight line, we managed to significantly refine these settings for better performance.

3. Data Analysis

Our data analysis primarily revolved around the comparison of sensor readings with ground truth data:
•	Temperature and pressure data were analyzed to ensure the sensors' accuracy and reliability.
•	The discrepancies observed, such as a sensor temperature of 36.6°C vs. an actual 14°C, highlighted the need for better calibration and potentially more sophisticated sensors, as well as better sensing methods. 
These observations led us to propose improvements such as employing high-accuracy sensors located away from interfering components and developing a transfer function to correct consistent errors.

5. Encountered Issues

Several issues were encountered during the project:
•	GPS Functionality: The rover did not respond to GPS inputs correctly and behaved unexpectedly, such as moving in reverse.
•	Battery Dependency: The rover's performance was heavily dependent on the battery charge level, affecting its speed and test completion.

Solutions Implemented

•	Multiple tuning sessions were conducted to eliminate navigational errors.
•	Rotating the Navio board and recalibrating the sensors addressed the GPS issues, restoring its functionality.

Conclusion

This project not only enhanced our technical skills but also taught us valuable troubleshooting techniques. The iterations in tuning and data analysis have prepared us better for future projects, where we aim to integrate more robust systems and achieve higher precision in autonomous operations.
