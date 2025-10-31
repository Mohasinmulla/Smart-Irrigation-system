# Smart-Irrigation-system

## Overview
This project is a Smart Irrigation System designed to optimize water usage for agriculture or gardening. The system monitors soil moisture levels and automatically controls water pumps or valves to irrigate plants only when necessary, saving water and promoting healthy plant growth.

## Features
- Real-time soil moisture monitoring using sensors  
- Automated water pump control based on moisture thresholds  
- Data logging for monitoring irrigation patterns on Blynk 
- User-configurable settings for irrigation timing and thresholds  
- remote monitoring through blynk   

## Hardware Components
- Soil moisture sensor  
- Microcontroller ( ESP32)  
- Water pump   
- Relay module (here i used 4 channel realy which is available for me) 
- Power supply  
- Connecting cables and mounting hardware  

## Software Components
- Arduino ide

## Installation
1. Connect the soil moisture sensor to the microcontroller analog input.  
2. Connect the relay module to control the water pump .
3. Create blynk account and setup for credentials to uplad data . 
4. Upload the firmware code to the microcontroller.  
5. Configure threshold values for soil moisture and irrigation intervals.  
6. Power the system and test functionality.

 ## Working Model

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/521aa3ca-ff4b-4462-983f-16b74df4222b" width="400" /></td>
    <td><img src="https://github.com/user-attachments/assets/c212c399-019e-445c-b164-973e33769c29" width="400" /></td>
    <td><img src="https://github.com/user-attachments/assets/1618d0bc-41fd-42fe-81a0-9c44485c41a5" width="400" /></td>
    <td><img src="https://github.com/user-attachments/assets/5ea81a9f-492d-429a-86b6-d6aa381b17d9" width="400" /></td>
  </tr>
</table>



## Usage
- Ensure all hardware connections are secure.  
- Monitor soil moisture levels via the provided interface or serial output.  
- The system will automatically irrigate when soil moisture is below the set threshold.  
- Adjust configuration settings as needed.

## Contribution
Contributions, issues, and feature requests are welcome. Feel free to check issues or submit pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or support, contact [mohasinmulla861@gmail.com] or open an issue on GitHub.

