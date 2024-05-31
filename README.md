### DataAnalysisV2
#---------------------------------------------------------#<br>
Data comparison tool by Joshua Harrison            <br>
For AD, 1to1 Asset Management, and Microsoft Intune<br>
#---------------------------------------------------------#<br>
<br>
-----------------------INSTALL-----------------------<br>
Unzip all contents into a directory.<br>
It may be more convenient to make a new folder, and unzip it there.<br>
The DataAnalysis.exe - Shortcut can be moved wherever you wish.<br>
This shortcut points to the .exe in the dist folder.<br>
<br>

-------------------------USE-------------------------<br>
This tool will automatically connect to AD to pull staff/student workstation data based off your school selection.<br>
This data will be cleaned, pulling the SN: from the description if possible.<br>
All District devices will be removed from the data.<br>

Be sure to export the files you wish to compare; 1to1 assets, autopilot, intune.

1to1: Be sure you are exporting the columns "Computer Name", "Serial Number", "Asset ID", and "Asset Type"<br>
The other fields and the name of the file do not matter.<br>

Autopilot: Export the list from Devices>Enrollment>Devices<br>
https://devicemanagement.portal.azure.com/#view/Microsoft_Intune_Enrollment/AutopilotDevices.ReactView/filterOnManualRemediationRequired~/false

Intune: Export your list from Devices>Windows<br>
https://devicemanagement.portal.azure.com/#view/Microsoft_Intune_DeviceSettings/DevicesWindowsMenu/~/windowsDevices

The program automatically compares all the data sets and exports a spreadsheet with matches, exceptions, duplicates, and missing serials.

There is a README in the exported file if you require further explenation of each sheet.


For any questions, suggestions, bugs, or comments, please email me at <em>REDACTED</em>
