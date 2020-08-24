# Part 2

## Introduction to messaging for IoT Applications

In the first part of the workshop we explored the ESP8266 device and sensors, but to make an Internet of Things application we need to be able to connect the ESP8266 to the internet to be able to send and receive data.

In this part of the workshop we will use the CloudAMQP service we deployed on the IBM Cloud at the end of part 1 to enable you to collect IoT data using MQTT events, we will cover MQTT later in this section.

## Choosing a broker

In this section you will learn about the factors to consider when choosing the server, or broker, for your IoT application.

- Estimated duration:10 min
- Reading and research [Choosing an MQTT Broker](BROKER.md)

## Creating the initial application

In this lab you will pull together all the information from part 1 into a single app.

- Estimated duration: 15 min
- practical [**Create ESP8266 application**](APP.md)

## Introduction to the MQTT protocol

In this lab you will learn how to add MQTT messaging to an application.

- Estimated duration: 15 min
- practical [**Sending data to the Watson IoT platform using MQTT**](MQTT.md)

## Introduction to IoT Security techniques

In this Lab you will modify MQTT to use a secure connection.

- Estimated duration: 25 min
- practical [**Securing the MQTT traffic using self-signed certificate**](CERT1.md)

## Additional security considerations

In this lab you will look at options for additional security.

- Estimated duration: 10 min
- practical [**Additional Security considerations**](CERT2.md)