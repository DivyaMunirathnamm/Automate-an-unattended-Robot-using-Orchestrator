# Automate-an-unattended-Robot-using-Orchestrator
# NAME:DIVYA M
# Register number:212223040043
# AIM:
To automate and execute an unattended Robot in UiPath Orchestrator by publishing a project from UiPath Studio, creating necessary assets and triggers, and running the process remotely.

# ALGORITHM:
Step 1:
Create and Publish a Project Open UiPath Studio and create a sample project (e.g., a Message Box or any automation). Save the project and click "Publish" to upload it to Orchestrator (Tenant Processes Feed).

Step 2:
Log in to UiPath Orchestrator Go to https://cloud.uipath.com and log in. Choose your Orchestrator tenant.

Step 3:
Provision Robot and Machine Go to Tenant > Machines: Add a Standard Machine with the same name as your device (check in Studio via Help > License Details). Under Tenant > Folders > Manage Access, ensure your user is assigned with proper roles (e.g., Robot role). Go to Tenant > Robots and create a Unattended Robot: Link it to the correct machine and user. Assign it to your folder.

Step 4:
Create Process in Orchestrator In Automation > Processes, click Add Process. Select the published package from the dropdown. Choose version, folder, and display name. Click Create.

Step 5:
Create Trigger to Schedule the Robot Go to Automation > Triggers. Click Add Trigger: Select your process. Set Trigger Type to Time. Choose the time, frequency (Once, Daily, etc.). Click Create.

Step 6:
Monitor Execution In Jobs, you can monitor the status (Pending, Running, Success, Faulted). View logs, time stamps, and robot execution details.

# PROGRAM:
<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/2f3cbb64-2d69-4f7c-a65c-4bd91290f937" />
<img width="1917" height="1021" alt="image" src="https://github.com/user-attachments/assets/fb1ffd92-5218-4a32-9e0f-60c2dc272ead" />
<img width="1919" height="1039" alt="image" src="https://github.com/user-attachments/assets/930528b8-fe12-4d82-8fb4-5fbaed99f857" />
<img width="1919" height="983" alt="image" src="https://github.com/user-attachments/assets/3ea1a876-7ab9-482f-9385-6e085475c7c8" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/d0f7d9ab-35e0-45ef-a2db-96a2e424c6ad" />
<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/041fa579-1598-4e04-ae90-d7ceffc1022b" />
<img width="1919" height="991" alt="image" src="https://github.com/user-attachments/assets/f2262492-27e0-4fb8-9ee8-9043ef0aaf64" />
<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/a56512dd-1cab-419c-b693-dee37cc285e7" />
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/0623c2b8-5223-47be-9648-a18a0e4e3990" />
<img width="1919" height="1025" alt="image" src="https://github.com/user-attachments/assets/a8bca346-f95a-42f6-a4d0-f1f47c9591c5" />
<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/d48bb0e7-c233-4914-b908-73f6f55d7ae5" />
<img width="219" height="182" alt="image" src="https://github.com/user-attachments/assets/37db2100-939e-4a0f-8167-19a4f503aa13" />
<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/aa2e37ba-d0eb-48c6-ab26-9fd55366568f" />


# RESULT:
The automation process was successfully published, triggered, and executed as an unattended job using UiPath Orchestrator. This setup ensures automation can run without human presence at scheduled times.






