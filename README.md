# telegram-file-forwarder
telegram file forwarder, telegram dosya indirici
Download and save the main.exe file.

Create or download the settings.ini file and save it. This file should be in the same directory as the .exe file.

Open the settings.ini file with a text editor and enter the following information:
[telegram]
api_id = <API ID>
api_hash = <API hash>

[target_entity]
id = <target group ID>

[source_entities]
id_1 = <source group ID 1>
id_2 = <source group ID 2>

You can obtain the api_id and api_hash information from the Telegram API page. Enter your target and source group IDs in the target_entity and source_entities sections.

Save and close the settings.ini file.

Double-click the main.exe file to run it.

The program will continue running until it shows a message indicating that the files have been successfully transferred to the target group.
