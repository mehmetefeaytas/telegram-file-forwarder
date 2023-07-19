Python Telegram File Transfer Guide

This guide is prepared for those who want to transfer files on Telegram using the Python programming language. The guide explains how to transfer files to a target group using the telethon library.

Requirements
To run the program, you first need to install the telethon library. You can use the following command for this:

pip install telethon

The program also requires the asyncio and configparser libraries to run. However, since these libraries are among the standard libraries of Python, users do not need to install them separately.

Settings
To run the program, you need to create a file named "ayarlar.ini". This file must be in the same directory as the .exe file. The information that should be included in the ayarlar.ini file is as follows:

[telegram]
api_id = <API identification information>
api_hash = <API authentication code>

[target_entity]
id = <target group ID>

[source_entities]
id_1 = <source group ID 1>
id_2 = <source group ID 2>

You can obtain the api_id and api_hash information from the Telegram API page. Enter your target and source group IDs in the target_entity and source_entities sections.

Running the Program
Download and save the main.exe file.
Create or download and save the ayarlar.ini file. This file must be in the same directory as the .exe file.
Open the ayarlar.ini file with a text editor and enter the necessary information by following the above steps.
Save and close the ayarlar.ini file.
Double-click the main.exe file to run the program.
The program will continue to run until it displays a message indicating that the files have been successfully transferred to the target group.
