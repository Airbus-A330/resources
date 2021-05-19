# Linking your Github Account!

Linking your GitHub account to your Discord account within the server will get you the "GitHub User" role. In the future we plan on adding further perks and features for verified GitHub users.

*`Note:` Linking your GitHub to Discord using traditional means will not result in the desired outcome. Due to Application Programming Interface (API) limitations, our bot is not able to see what account is linked if any.* 

### **Steps:**

 - [ ] Get verification key from OctoCat
 - [ ] Place verification key in Github Bio
 - [ ] Get OctoCat to verify your key and link your account

### Prerequisites:
- Direct Messages enabled for the Github Community Discord Server
- GitHub Account (You will need to enter sudo-mode to edit your bio. Make sure you have your password.)

## Get a Verification Key

In the [#bot-commands](https://discord.com/channels/811436417824718878/826853132600344576) channel, run `git link -generate`. The bot will do one of two things.

 1. It will react with a checkmark. 
 *Like this:*
 
 
 ![Image shows a member using the command and it working correctly.](https://cdn.discordapp.com/attachments/778594651409219615/844595911497089085/Screen_Shot_2021-05-19_at_11.20.45_AM.png)
 
 
 2. It will respond with an error message.
 *Like this:*
![Screenshot of error message displayed if you are unable to recieve DMs from the bot.](https://cdn.discordapp.com/attachments/778594651409219615/844595908431970334/Screen_Shot_2021-05-19_at_11.21.12_AM.png)

If you get the error message, that means the bot is unable to DM you. You can resolve this by temporaily enabling DMs for the server. This can be done in privacy settings. To access Privacy Settings, first right click the server, and press "Privacy Settings" 
![Screenshot from Discord Desktop Client of right clicking the server icon and hovering over "Privacy Settings"](https://cdn.discordapp.com/attachments/778594651409219615/844597242727759933/Screen_Shot_2021-05-19_at_11.27.37_AM.png)

Next, make sure `Allow direct messages from server members.` is set to TRUE, as shown.
![Image shows Discord Privacy Settings for server "Github Discord Community" with direct messaging from server members set to true.](https://cdn.discordapp.com/attachments/778594651409219615/844596687170830406/Screen_Shot_2021-05-19_at_11.25.04_AM.png)

The bot will attempt to send you the DM for a second time after 30 seconds. If you fail to complete the steps fast enough, and do not get the second attempt, please run the ``git verify -generate`` command again. *Do not run it before thirty seconds, it will generate two verification keys, and will cause issues.*

When the command works successfully, you will get a DM from OctoCat, this DM will contain your verification key, and some short instructions. An example of this DM is shown below.
![Image of DM sent from OctoCat for verification purposes.](https://media.discordapp.net/attachments/778594651409219615/844600112684072960/Screen_Shot_2021-05-19_at_11.34.29_AM.png)

Congrats! You have your verification key, now copy this to your clipboard and proceed to the next step.

 - [x] Get verification key from OctoCat
 - [ ] Place verification key in Github Bio
 - [ ] Get OctoCat to verify your key and link your account

## Adding the Verification Key to your GitHub bio.

Head to your GitHub Profile Settings ([https://github.com/settings/profile](https://github.com/settings/profile)). Then find the field that says `Bio`, this is where you need to put your verification key. It does not matter if you have anything else in your bio, it just needs to be in the bio somewhere. View image below for location of the field. 

![Image shows GitHub Profile Settings Page with Bio field in red](https://cdn.discordapp.com/attachments/778594651409219615/844601596150415420/Screen_Shot_2021-05-19_at_11.44.47_AM.png)


Paste the verification key into your Bio. Then continue on to the next step.

 - [x] Get verification key from OctoCat
 - [x] Place verification key in Github Bio
 - [ ] Get OctoCat to verify your key and link your account

## Get OctoCat to verify your key and link your account

Now, go back to Discord and run `git link -verify [GithubUsername]` where `[GithubUsername]` is your GitHub Username. The bot will then verify your account if you have correctly completed all steps you will see this message.

![Successful verification message](https://media.discordapp.net/attachments/778594651409219615/844602907823177758/Screen_Shot_2021-05-19_at_11.50.20_AM.png)

You have successfully completed all the steps and your GitHub Account is linked! We have a few more notes below if you wish to read them!
 - [x] Get verification key from OctoCat
 - [x] Place verification key in Github Bio
 - [x] Get OctoCat to verify your key and link your account

## Notes

- In the future this process will likely be moving to an OAuth system through GitHub Nativley. This will simply the process.
- As we said earlier, other perks and features will likely be added to the verified users.
- You are welcome to remove the verification key from your bio after verifying. It is not nessecary.
- You can DM OctoCat at any time for further assistance.
