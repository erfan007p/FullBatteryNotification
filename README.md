# FullBatteryNotification
Repo containing scripts to notify your battery charged fully on your laptop

- Adjust `Your_Folder_path\ToastNotification.ps1` in FullBattery.vbs with your folder path where you saved the mentioned file
- Copy the VB Script file and paste in your startup folder `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp`
- Now once you restart your laptop, VB Script will start running on background and the same will check if the battery is charging and also if the battery percentage is greater than 95. It will check the same on every 5 minutes.
- You can adjust the battery percentage value and the delay time according to your need.

Credits : https://gibinfrancis.medium.com/laptop-battery-full-charge-notification-c770e446e84c
