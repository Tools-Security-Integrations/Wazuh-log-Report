# Wazuh-log-Report
Hey all,
My name is vaibhav.

Wazuh Log Report Visualizer

If you've used Wazuh, you may have noticed that the log reports can be difficult to interpret and lack detail. To address this issue, we've developed a Python script that converts your JSON log file into a more user-friendly Excel report.

Features:
Converts Wazuh JSON log files into Excel reports
Allows you to specify which fields from the JSON log file to include in the Excel report
Easy to use - simply change the IP address and Wazuh login credentials in the script and ensure that your JSON file has the correct permissions

Pre-Request:
Install the required libraries by running pip install
pandas
openpyxl

Installation:

Download the Python script from this repository

Update the ip_address, username, password, and json_file_location variables in the script to match your Wazuh setup
Run the script using python.

Usage:

The script will generate an Excel report in the same directory as the script, containing the specified fields from your Wazuh JSON log file.
Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
