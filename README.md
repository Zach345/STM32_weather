# STM32_weather

Using the STM32L476R_NUCLEO-L476RG microprocessor to communicate with an ESP8266 ESP-01s WIFI module to connect to a Wi-Fi network. Then establish a verified HTTPS connection to the AccuWeather API to request Cookeville's hourly forecast. Parse the JSON and extract the fields needed to send a short message to the STM32 over UART.

The STM32 microprocessor will display the hourly temperature along with weather conditions to a LCD (for the moment)
