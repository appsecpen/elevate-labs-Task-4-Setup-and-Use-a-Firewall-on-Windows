
Task 4 – Setup and Use a Firewall on Windows

Objective:
Configure and test basic firewall rules to allow or block traffic using Windows Defender Firewall.

System Used:
Operating System: Windows 10/11  
Firewall Tool: Windows Defender Firewall with Advanced Security

Steps Followed:
1. Opened "Windows Defender Firewall with Advanced Security".
2. Navigated to "Inbound Rules" and clicked "New Rule".
3. Selected "Program" and chose the Chrome executable:
   C:\Program Files (x86)\Google\Chrome\Application\chrome.exe
4. Chose "Block the connection".
5. Applied the rule to all profiles: Domain, Private, Public.
6. Named the rule: "Block Chrome".
7. Verified the rule was created and enabled.

Verification:
The attached screenshot shows the rule "Block Chrome" listed under Inbound Rules with:
- Profile: All
- Enabled: Yes
- Action: Block

Deliverables:
✔ Screenshot of the rule: "Output Block Defender Firewall.jpg"  
✔ README.txt (this file)
