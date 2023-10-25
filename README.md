# RedTeamTool
Windows 10 c2 backdoor based off the villain tool, obfuscated to avoid windows defender detection

**TO USE**
- Attacker machine:
  1. Make sure you have the villain package installed, either through apt or via [this repo]([url](https://github.com/t3l3machus/Villain)https://github.com/t3l3machus/Villain)
  2. Run the command **villain** to start the session listening server - this will automatically begin listening for session connections

- Target Machine:
  1. Replace '192.168.253.128' in the ps1 script with the IP of your attacker machine
  2. OPTIONAL - replace '4443' with the desired port for your connection - ONLY IF YOU CHANGE VILLAIN'S DEFAULT LISTENING PORT
  3. Execute the ps1 script on the target Windows machine
