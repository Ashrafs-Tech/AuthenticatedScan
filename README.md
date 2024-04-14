# Authenticated Scan Execution 

## Intro

In order to execute the scan:
- I will create a new scan target and click save.
![VL 39](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/7af79bce-1c2c-4239-9588-fb7b0c7d851e)

- The new task will log into the virtual machine and do a deep credential scan to discover more vulnerabilities.

- Below are the results of the new scan. A lot of new ones
- Adobe Reader, Firefox, and VLC have a ton of issues.

![VL 40](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/86256cd9-14d1-4a7a-aed1-21f1d94fdc8d)

![VL 41](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/0fb00da0-fbb6-4e33-a4c5-b9147db6741c)

![VL 42](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/d721fbc9-75b6-4b22-b9fd-059b5f5e100b)


- I can click on them and see the description of each vulnerability.
  * As seen with the Firefox issue below

![VL 43](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/7c06c0af-adcf-4446-82e7-4ceb20a25181)

- Besides the description, the impact of the vulnerability and the solution is also listed.

![VL 44](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/9c3654f1-7190-495a-bade-8f7b3c69adfa)

- Now I will go back to the Windows virtual machine.
- One way to remove the vulnerabilites is uninstalling them and then run a credential scan again to observe the findings.
- I went to the control panel in the Windows virtual machine uninstall.

![VL 45](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/5f8c5ac0-4c8f-47d1-a855-e74595d2af98)

- After installing Adobe, Firefox, and VLC, I will restart the virutal machine.

- Then I will go back to OpenVAS tasks to do a rescan.

- After the scan is complete, there will be a trend line that's going down.
  * This refers to the amount of vulnerabilities decreasing.

![VL 46](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/25ae653d-9286-466d-ad34-71f85a2c5c6f)

- Then I clicked on the report and view the results. Less vulnerabilites appeared.
- No more Adobe Reader, Firefox, and VLC issues.

![VL 47](https://github.com/Ashrafs-Tech/AuthenticatedScan/assets/166546026/da6a6613-d336-49c6-9784-80738d077033)


## Step 7 is done





