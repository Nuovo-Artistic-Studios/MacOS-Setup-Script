# Ultimate Mac OS Setup Script

## How to run this script on Mac OS

##### 1. Go through the initial steps prompted by the OS to create a user and settings (user has to be "superadmin" in one word, with the password associated to it on LastPass / Google Workspace)

##### 2. Open Terminal

##### 3. copy / paste the following line into your terminal:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Nuovo-Artistic-Studios/MacOS-Setup-Script/main/macos.sh)"
```

##### 4. Enter Superadmin Password 4 times when prompted

##### 5. At the very end of the script, TrimForce will engage (requires manual input). Just press "Y" twice (to confirm), if successful, your mac will reboot.

##### 6. Once rebooted, log back in to the superadmin account, and install the [**JUMPCLOUD MDM PROFILE**](https://it.nuovo.technology/profile_jc.mobileconfig) manually.

##### 7. Once installed, the agent will auto install on the mac and the computer will show up on Jumpcloud.

##### 8. From there, you can select the "Superadmin" Account on Jumpcloud, along with any other user(s) and policies and push them onto the Mac.
