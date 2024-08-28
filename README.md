# Wazuh-log-Report
Hey all,
My name is vaibhav. Read carefully before use. 

Wazuh Log Report Visualizer

If you've used Wazuh, you may have noticed that the log reports can be difficult to interpret and lack detail. To address this issue, I have developed a Python script that converts your JSON log file into a more user-friendly Excel report.

This script will run on your windows machine and after exicuting the script will auto login to your wazuh-server using SSH and fetch current date json log file into your windows local machine and convert into detail excel formate, you can also change the fields according to your need.

Features:

1.Converts Wazuh JSON log files into Excel reports

2.Allows you to specify which fields from the JSON log file to include in the Excel report

3.Easy to use - simply change the IP address and Wazuh login credentials in the script and ensure that your JSON file has the correct permissions

4.you can also change the fiels according to your need to convert in excel.

5.This script is capable to auto fetch your json file from wazuh server and convert into json.


Installation:

1.Download the Python script from this repository.

2.Update the ip_address, username, password, and json_file_location variables in the script to match your Wazuh setup
Run the script using python.

3.just run this script in visual studio and once you have done yoou can also convert this script into exe for your windows machine.
Usage:

The script will generate an Excel report in the same directory as the script, containing the specified fields from your Wazuh JSON log file.

Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



Note: 
if you want an script that will inhance wazuh capabilities please feel free to mail on vaibhavhandekar3@gmail.com.
