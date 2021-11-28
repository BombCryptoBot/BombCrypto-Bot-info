# BombCrypto - Bot (V1.1)

This is a fully automated script that manages your account(s) 24/7, letting you rest the entire day while your heroes work.
This is not OpenSource software, as we believe that this needs time, dedication, and a lot of work to create a safe and secure bot for all our accounts.

This bot works looking for image patterns on the screen and controlling the mouse functions as a real person would do.

Want to know more? Get into our Discord channel at https://discord.gg/tZ6a2HbK9q


## **How this bot works?**

- This bot uses python3 as a primary development language, so feel free to see the code and ask for changes.
- This bot can be used directly at your desktop or inside a VM (Multiple-accounts allowed using virtual machines, so each one can control a single mouse)
- This bot doesn't ask for wallet addresses, secrets, metamask password, and anything else!
- It uses your own firefox profile (already logged in into metamask with a stored password to unlock).
- It recognizes in what "step" your account is, (Loggin, Working, Resting and so) and control the browser to ensure your account is working all the time.

You can see it running here: https://vimeo.com/650831729


## **What does this bot do?**
- Unlocks your metamask wallet
- Connect the wallet to the game
- Sign the wallet to the game
- Monitor farming
- Send heroes to work- Go to next map when appearing
- Solves "unknow error" alert- Solves "manual error" alert- Wait for server maintenance end to re-login
- Solves the issue when there is only 1 box on the map and hero's keep running away from the chest- Can configure how much time the bot will wait working into the map (team power/time to rest)


## **What does this bot don't do?**
- Send heroes to house (Work in progress)
- Clain heroes (Feature may never be on the code due to security reasons)
- Clain BCOINS (Feature may never be on the code due to security reasons)


## **How to install**

**Requirements:**
- Any Linux distribution
- Firefox installed
- Python3 and PIP3
- OpenCV Installed
- No power-saving settings on
- No screensaver settings on

There is 2 ways to install the bot:


### Method 1) Self desktop installation
If you want to use your own desktop as installation media, you need to create a new firefox profile:

```bash
$ mkdir ./new-profile-folder && firefox -profile ./new-profile-folder
```
This command will create a new firefox profile into the known folder and also open firefox for you.
When firefox open, make sure to follow these steps:

- Go to settings, search for language and change the language to Portuguese (Brazil)
- Install metamask addon
- Create/Import your wallet, make sure to "store password" (as the bot don't know your password, this is the easiest way to unlock the wallet without "sharing" your password)
- Go to http://app.bombcrypto.com and connect your wallet (don't need to sign the login, just connect the wallet)
- Exit firefox

After configuring your firefox account, we need to install python requirements:
```bash
$ pip3 install -r requirements.txt
```

After this process, your bot is ready to run:
```bash
$ python3 main.py -fp ./new-profile-folder
```


### Method 2) Installing into a virtual machine
So you want to run multiple accounts? Se we do!

- Install "virtual box" or any other virtualization software (as Boxes, VMWare, etc).
- Create a new Virtual Machine with at least: 3 cores, 2gb memory, and 128MB of graphics memory.
- Install any Linux distribution you like, we recommend Lubuntu as it is a lightweight Debian distribution and easy to use.
- Remove all power-saving settings
- Remove all screensaver settings
- Install Python3
- Install Python3-pip
- Install OpenCV
- Install all python requirements
- Follow "method 1" to run the bot on the new machine


## **F.A.Q.**

**Q)** Will my account be banned using this bot?\
**A)** As far we can tell, there is no rule against automatization into BombCrypto, and if so.. the game was built as a web game that renders Unity over WebGL (Wich has no API to detect what's running outside the browser sandbox, also there is no browser automation (like selenium) so the JavaScript API has no rights to overscale permission into OS to detect too)

**Q)** Will I be able to open multiple accounts with this bot?\
**A)** Yes. The limit of multiple instances is the power of your computer running multiple VM's.

**Q)** How much does it cost?\
**A)** The actual price of the bot is 100 BCOINs.

**Q)** How to buy this bot?\
**A)** You need to get into our discord channel (https://discord.gg/tZ6a2HbK9q) and follow the instructions there.

**Q)** If I bought this bot, and the game gets an update the breaks the bot what happens?\
**A)** We'll provide regular updates to the bot users at our discord channel.

**Q)** Why Linux?\
**A)** This bot has been made to run multiple accounts, nothing is better for VM's than Linux instances, it uses less memory, less hard drive, and less work for the processor.

**Q)** Why firefox needs to be in Portuguese? I don't speak Portuguese, what I do?\
**A)** This will be solved soon as we implement the multi-language bot, for while the bot needs this to search metamask buttons (as it uses browser configuration to show the app). You can configure your firefox in English and change Firefox and Metamask settings to Portuguese later.

**Q)** Can I use this bot on my windows machine?\
**A)** It may work, but it was never tested and there is no support for Windows OS right now or planned.

**Q)** What's the difference between this bot and the free ones?\
**A)** Our bot was made by a team of developers that works with professional automation for data mining on a big scale, it is meant to be fast, precise, undetectable and solve any issue that appears while the bot is running, ex: Server down, maintenance, socket disconnection and so.

**Q)** I've seen on the internet this bot for free, why?\
**A)** Sadly, it can happen due to few people that share the code with friends or over the internet. We don't recommend you use this kind of bot, it may be edited to steal your wallet.