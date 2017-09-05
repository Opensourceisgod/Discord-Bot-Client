# Discord Bot Client

[Discord]'s client is great, but doesn't allow you to control a [Bot User] account.

## About

### What this will let you do

With this application, you will be able to fully control your [Bot User] account, like sending people a DM.

### Disclaimer

This application is very Bare-Bones, and is not close to being complete, It is currently more of a "Proof of Concept".  I will keep working on this with more improvements and features to try to let this application run as close to the native Discord client as I can get.

### Long-Term Plans

My end goal with this project is to create a client very similar to the native Discord client as I can.  There are a few minor things I can not currently add to the app, such as the [Audit Log].  This app runs with [Discordie] as a base, and that framework does not yet support the [Audit Log].  I would also like to allow this app to have plugins so it can run bot commands as a Self-Bot would, but, because it is built into the program, it will run much quicker.

### Current Feature List

* Get a direct message list<sup>1</sup>
* Send and receive direct messages
* Notifications on a new message

<sup>1</sup>Discord itself does not store a direct message list for Bot Users, and so it will not show up.

### Immediate To-Do List

* Ability to/to show Edit/Delete messages
* Ability to show/send Images
* Ability to show/send Attachments
* Ability to infinitely scroll up to see past messages

### Known Issues

* You have to click on a certain part of the Direct Message in the list to mark it as read.
* There are no real error messages to let you know what is going on
* The visual design is bad

### What I Will Never Add

* Video Calling
  * Video calling requires the ability to call in a Direct Message, and bots can't call in a direct message

## Installation

Currently there is no compiled version of this app, and so you need [Node.JS] to be installed in order to run this.

1. Download this Git and extract it into a folder
2. Create a text file called `token.txt` and type your Bot User's token in the file
3. Open your Terminal/Command Prompt then use `cd` to open the directory of your folder
4. Type `npm install` to install the required Node Modules for this application
5. Type `npm start` to start up the Application

## Usage

**To open a new DM**
Get the recipient's Discord ID and enter it in the text box at the top left, then click "add".

**To Send a message**
Click on the recipient's name in the list to the left, type your message in the text box at the bottom, then click your "enter"/"return" key

[Discord]: https://discordapp.com
[Bot User]: https://discordapp.com/developers/docs/topics/oauth2#bot-vs-user-accounts
[Audit Log]: https://blog.discordapp.com/5-3-17-change-log-a9239d5321dd
[Discordie]: https://qeled.github.io/discordie/
[Node.JS]: https://nodejs.org/en/
