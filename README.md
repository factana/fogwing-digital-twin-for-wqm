# Fogwing IoT digital twin  simulator program for WQM with Raspberry Pi
This directory provide two files that sends sample data over Fogwing IoTHub.

## Fogwing IoT Simulation for WQM
We have provided three files:
* [requirements.txt](https://www.google.com)
* [Fwg_digital_twin_for_WQM.py](https://www.google.com)
* [configuration.json](https://www.google.com)

Fwg_digital_twin_for_WQM.py file is for sending the data over Fogwing, 
it keeps sending data with every minute or hour gap as per requirement 
until programs stop manually (Ctl+C) 
and configuration.json is for configuring the required credential of
Fogwinf IoTHub and sample data.
 
 ### Step:1
 #### Python & json file
 * Copy the python file and json file to your raspberry pi, now you have completed coding part.
 
 ### Step:2
 #### Installing the libraries
 * Install all required libraries using pip with our requirements.txt file.
    ```
    pip install -r requirements.txt
    ```
 
 ### Step:3
 #### Credentials 
 * Change the **client_id**, **username**, **password** with
   your Fogwing IoTHub access credentials and **time_interval** in **configuration.json** file.
   
 ### Step:4
 #### Run and Get Started with Fogwing IoT
 * Now run the file with the below command.
    ```
    python Fwg_digital_twin_for_WQM.py
    ```
    **Note:-** Provided everything goes in line with the above mentioned
               instructions,you will be able to see a message that reads 
               'successfully published' in command line.
               
 ### Step:5
 #### Start Analyzing your Data at Fogwing Platform
 * Now you are ready to analyze your data at [Fogwing Platform](https://community.fogwing.net/) portal,
   you can check all the data within the data logs in the portal.
 
 #### Getting help and finding Fogwing docs
 * [Fogwing Community Forum]()
 * [Fogwing Community Docs](https://docs.fogwing.io)
