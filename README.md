Kaisar Network:

The Universal AI Compute Layer. Your Compute, Your Currency.<br>
![GxAmD-jbkAAAwHK](https://github.com/user-attachments/assets/20c3b283-8f32-4af0-8f95-3e7b81569f40)

Kaisar Provider CLI Installation Guide for Contributing to Kaisar Network<br>
Requirements:<br>
Memory: 4GB RAM<br>
Processor: 64-bit CPU with virtualization support<br>
Storage: 100GB HDD/SSD<br>
Internet Speed: 100Mbps or higher<br>

Rent a VPS<br>
VPS is (Virtual Private Server that runs 24/7)<br>
Order Here: (Use the Link and Euro(€) For Discount):<br>
https://www.tkqlhce.com/click-101512553-13484397


I recommend to run this on VPS20 > Region Any> Storage Type 400GB SSD> Ubuntu v22.04> Log in Password (Don’t forget) > 6–8 settings default only > Click Next >
Fill up your details > Payment.<br>
“I used Gotymebank or Maya(both vitual cards) link to Paypal(all are perfored in the website). You will pay €12.25 or 800+ pesos[No Set Up Fee  with Claim 6.⁰⁰ Credit Back].”<br>
Once Paid > Wait for the Email to Arrived > Follow instruction.<br>
“Personally I’m using VPS30, to sustain my other Nodes”<br>


Setting up on Your Laptop/PC Windows:<br>
Now you have your own VPS server.<br>
Download putty.org > log in to your IP there.<br>
After Connected, We can now Start.<br>
Still Confuse? More Guide in VPS Access:<br>
https://www.facebook.com/share/p/zhHCh3773653iXZF/<br>
You have now your own Ubuntu(Linux Server) that runs 24/7 in other country. <br>
Let’s Navigate!<br>


On Terminal 
Copy and Paste the Following Commands:

# Prerequisites:
sudo apt update -y && sudo apt upgrade -y

# Create a Screen
apt install screen -y <br>
screen -S kaisar <br>

# Install npm and node js. 
apt install npm -y <br>
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash <br>
source ~/.bashrc <br>
nvm --version <br>
nvm ls <br>
nvm ls-remote <br>

# I choose v20.15.1
nvm install v20.15.1

# Install pm2
sudo npm install -g pm2
# Install script
curl -O https://raw.githubusercontent.com/Kaisar-Network/kaisar-releases/main/kaisar-provider-setup.sh

<img width="1434" height="309" alt="Screenshot 2025-08-10 at 7 19 42 PM" src="https://github.com/user-attachments/assets/514fe56c-8936-42ec-b171-7cd258397d23" />

# Make the Script Executable
chmod +x kaisar-provider-setup.sh

<img width="745" height="253" alt="Screenshot 2025-08-10 at 7 20 55 PM" src="https://github.com/user-attachments/assets/aeb7a86b-68e6-4c72-a56a-c5dae85f2991" />

# Run the Setup Script with Root Privileges
sudo ./kaisar-provider-setup.sh

# The script will automatically:
Install Node.js, npm, and pm2 if not already present
Download the latest release of Kaisar Provider CLI
Install all required dependencies
Set up the CLI globally on your system
<img width="1027" height="663" alt="Screenshot 2025-08-10 at 7 22 18 PM" src="https://github.com/user-attachments/assets/fb66dc50-8439-40ef-8c16-73340c0720bf" />

# Verify the Installation
After installation, verify by running:
kaisar

If you see a welcome message, the installation was successful!
<img width="750" height="469" alt="Screenshot 2025-08-10 at 7 23 12 PM" src="https://github.com/user-attachments/assets/79f6897b-c575-4064-b963-74bbde585ad4" />

Start Using the CLI <br>
You can now join the network with the following commands: <br>

kaisar start          # Start the Provider App <br>
kaisar create-wallet -e <your email> # Create Wallet<br>
kaisar import-wallet -e <your email> -k <your private key> # Import your existed wallet<br>
kaisar status         # Check node status<br>
kaisar log            # Check details log of Provider App<br>

For easier:<br>
kaisar start<br>

kaisar create-wallet [Saved everything]<br>

kaisar status [Copy machine addresss] <br>

Paste it : https://onenode.kaisar.io/provider<br>
<img width="1327" height="807" alt="Screenshot 2025-08-10 at 7 26 07 PM" src="https://github.com/user-attachments/assets/4b67b7a8-dc19-40a9-a343-280a7af78e43" />

It will accumulate daily.<br>
For Logs: <br>
kaisar log<br>

#Detach from the Screen<br>
Before exiting, use CTRL + A + D to safely detach from the screen session.<br>
To reattach to the running node screen, use:<br>
screen -ls<br>
screen -r (name of screen<br>
Viola! 🥳<br>
You are now running Kaisar Network and can Back anytime to logs. 🤖<br>

<img width="1363" height="766" alt="Screenshot 2025-08-10 at 7 28 02 PM" src="https://github.com/user-attachments/assets/c17b0a6c-8e48-4869-bb16-da3729b2a037" />


Disclaimer:<br>
This is for educational purposes only, especially for those who are interested in studying or running DePIN/Nodes.<br>
No money is involved, and rewards are not guaranteed.<br>
Install and run at your own risk.<br>

Many are asking my tip function, there you are! Tips are highly appreciated.<br>
Wallet: 0x51AC7a95C1675bF5Ffb86a90b6F49cE0AA3A4da3<br>
Buy me Coffee: https://www.buymeacoffee.com/cryptobike<br>
Still Confuse behind those Nodes Tutorials? Enroll Now: https://buymeacoffee.com/cryptobike/commissions<br>






