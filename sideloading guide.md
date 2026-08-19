# This guide will help you with installing mond onto your iOS/iPadOS device.
## Please follow all instructions thoroughly, as we don't want to provide support for this 24/7.
## The quide goes from the point from where you already have the mond.ipa file on your device. 
## We will not give support in the mond Discord server, if you read the guide, and follow steps correctly, it will work.
## You can use this guide to sideload GestaltEdit also, follow the same steps freely.

## There are multiple methods, choose one by your liking.

# SideStore

### Because SideStore have made a guide themselves, which is literally good, use that. Guide: [SideStore Guide](https://docs.sidestore.io/docs/installation/prerequisites)

# AltStore

### Same case with SideStore, they also made a guide.
### Windows: [Windows Guide for AltStore](https://faq.altstore.io/altstore-classic/how-to-install-altstore-windows)
### macOS: [macOS Guide for AltStore](https://faq.altstore.io/altstore-classic/how-to-install-altstore-macos)

# Impactor (Highly suggested by the mond team)

### Impactor has a guide available aswell. [Impactor guide](https://impactor.claration.dev/docs/introduction/)

# WSF method (You only need your phone) (hard, if you have a computer, i'd rather use Sideloadly) (USE SAFARI!!!)

### Step 1: Open the website.

- Click this: [WSF website](wsfteam.xyz)

### Step 2: Installing the DNS.

- On the site, click Downloads
- Click Config Profiles
- Click "Michelle's DNS", this will send you to another website.
- Here, check the .mobileconfig file by clicking the little Square at the left, and click Download.
- Once the pop-up appears click Download.
- Click the little arrow down icon on your address bar
- Once the menu appears click Downloads
- Click the magnifying glass icon next to the file, this will open files.
- Click the DNS profile, which you downloaded.
- After clicking it, it will say "Profile Downloaded"
- Click close.
- Exit files, and Open Settings, under your name or family settings it should say "Profile Downloaded", click it.
- Click Install, enter your Passcode if needed.
- Click Install again.
- Click the checkmark icon.
- Click the arrow back icon from VPN and Device Management, and scroll down in General, click VPN and Device Management
- Under "Restrictions and Proxies" see DNS, and look at which one is picked.
- If "INSTALL Apps (Sideload) is picked, that's good.
- Exit Settings, Open Safari
- Click back 2 times to get back to Downloads.

### Step 3: Downloading certificates.

- On the site, click Certificates.
- Click Certificates
- Click download once asked to.
- Click the download button on the address bar
- Click downloads
- Click the magnifying glass, this will open files
- Extract Certificates.zip by clicking it, and it will create a folder named Certificates.
- Go back to Safari, close the Downloads page.
- Click Back. You should be at the Downloads page.

### Step 4: Installing Portal.

- Click Portal
- Here, a list of Portal will popup.
- Select the top one, don't click the IPA one.
- Click Install
- Exit Safari.
- Once it loads, try to open portal.
- If it says "Unable to Install Portal" then navigate back to Safari, and try all the other Portal download links, until one works. (in my case, Rural worked). If all does not work, you are blacklisted by Apple. To remove Blacklist, please follow this guide: [WSF Revoke fixing guide](https://wsfteam.xyz/guide#fixing-revokes)
- If Portal actually installed for you without errors, click it.
- It will say "Untrusted Enterprise Developer" this is good.
- Open Settings, go to General > VPN and Device Management.
- Select the company name, then on the top, click Trust "[company name]"
- Click Allow and Restart. This will reboot your iPhone.
- Once your iPhone boots up, it should show a screen "Ready to Install Profile"
- Swipe up from the bottom
- Click Install Profile (the red button)
- Enter your passcode if prompted.
- Your iPhone will boot up into iOS.
- Now, try to open Portal, it should work.

### Step 5: Configuring Portal, installing mond.

- Since Portal is a modified version of Feather, it will be pretty familiar for some people.
- Click Settings in Portal
- Go to Certificates
- Click the Plus Icon.
- Click "Import Certificate File"
- This will open up the File browser.
- Go to wherever your Certificates folder is which we extracted earlier.
- Here, **select the folder of the certificate you installed Portal with. This is very important.** For me, this is Rural. For you it might be different.
- Click the corresponding folder
- Click the corresponding .p12 file.
- Click "Import Provisioning file"
- Files should open in the same folder where you selected the .p12
- click the [your cert's name].mobileprovision file.
- Go to Enter password.
- Enter the password, which is "WSF". Capitalized.
- For the name, you can enter anything you want.
- If it says "Bad password" Just close portal, and reopen it, redo the whole certificate process.
- Go to Library
- Click the plus icon
- Click "Import from Files"
- Navigate to mond.ipa in your files.
- Select it, click open.
- Once mond appears on the list, click Sign.
- Click "Start signing" on the bottom.
- Go to "Signed" and click the green button with days.
- Wait a bit while mond Installs.
- If mond doesn't install, go to Settings.
- Go to the Installation tab.
- Make sure you set Installation to Server, and change the Server type to Semi-Local. (it works better tbh)
- Go back to Library, try Installing again.
- If a webpage comes up with "Open this page in iTunes?" Click Open.
- Then, click install.
- Exit Portal.
- You're done.

### Now you should have mond on your iDevice. Enjoy.


##### guide made by [ThatAppleUser](https://x.com/ThatAppleUser_).
##### we are not affiliated with Sideloadly, WSF or anything mentioned above. Everything is used at your own risk.


# Deprecated methods (They work, but there are easier ones available.)

<details>
  <summary>Sideloadly, Last case scenario, if nothing works. Click to expand.</summary>
  
  # Sideloadly (you need a PC or Mac)

### Please make sure you have all of the following:

- Charging cable,
- Your Apple Account password and E-mail, and the ability to view verification codes.

### Step 1: Installing Sideloadly.

- Hop onto the [Sideloadly website](https://sideloadly.io) and download Sideloadly for the OS you have.
- Install it onto your computer (this is pretty straightforward.)

### Step 2: Configure Sideloadly

- Click the gear icon in Sideloadly <img width="24" height="24" alt="image" src="https://github.com/user-attachments/assets/b0c9bc49-1ab7-49d5-8b40-42b4489e33ae" /> which can be found next to the device picker field.
- Once in Settings, under Anisette authentication pick: Remote. This will bring up a popup.
- Here, click "Login" which will bring you to the Patreon log in page. Info: You don't need to pay.
- Here, Just create a Patreon account, or sign into one.
- Once you're done with that, reopen Sideloadly
- Click OK

### Step 3: Install the IPA

- Click that IPA icon, which will bring up a file explorer, or Finder on Mac.
- Pick the mond.ipa file, and open it.
- Plug your iPhone/iPad in to your computer.
- If not automatically picked, click the device selection field, and pick your iDevice.
- Enter your Apple Account Email Address into the Apple ID field.
- Click Start.
- Once Sideloadly brings up "Enter your AppleID password" enter it. (Don't worry. Your data is not getting sent neither us, or Sideloadly.)
- If it asks for a verification code, enter it.
</details>
