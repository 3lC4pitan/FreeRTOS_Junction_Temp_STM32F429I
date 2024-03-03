# Junction Temperature Application

This project is an application developed for monitoring and managing the junction temperature of a microcontroller, specifically designed for the STM32F746ZG microcontroller. The application provides functionality to measure and display the junction temperature using various peripherals and sensors.

## Features

- **Temperature Measurement**: The application utilizes an integrated temperature sensor or an external sensor connected to the microcontroller to measure the junction temperature.
  
- **GUI Interface**: The application includes a graphical user interface (GUI) developed using TouchGFX, allowing users to interact with the application and view temperature readings.
  
- **Peripheral Initialization**: The project initializes and configures various hardware peripherals such as ADC, CRC, I2C, SPI, LTDC, DMA2D, and SDRAM to facilitate temperature measurement and GUI rendering.
  
- **Temperature Monitoring**: It continuously monitors the junction temperature and provides real-time updates to the user interface, allowing users to track temperature changes over time.
  
- **Error Handling**: The application includes error handling mechanisms to detect and handle any anomalies or faults in the temperature measurement process, ensuring reliable operation.
  
- **Configurability**: Users can customize the application settings, such as temperature measurement interval, temperature unit (Celsius or Fahrenheit), and temperature display format.

## Usage

1. **Hardware Setup**: Connect the STM32F746ZG microcontroller to the temperature sensor and any necessary peripherals as per the project requirements.
  
2. **Build and Flash**: Build the project using an integrated development environment (IDE) such as STM32CubeIDE and flash the generated binary onto the microcontroller.
  
3. **Run the Application**: Power on the microcontroller, and the application will start running automatically. Interact with the GUI to view real-time temperature readings and configure settings as needed.

## Contribution Guidelines

Contributions to this project are welcome! 

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
