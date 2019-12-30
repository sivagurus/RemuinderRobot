# remuinderrobot

Python Telegram BOT main features:
1. Store and retrive data from a database: you can save what you want and read it when you want. 
2. Set an alarm: when time is up the BOT will remind you what you asked for.
3. Exchange messages between strangers: store a message in unknown way. You can also send it for a certain person. In this way he/she will be able to read it but he/she will never know the writer of the message.  

Check it out on telegram: [@RemiunderRobot](https://telegram.me/RemuinderRobot)

# BOT usage

- ⭕ Developer
    - /about: to see info about developer
    
- 📝 List
    - /addtolist \<items>: to add one or several items to your personal list (to do list, reminders or what you want)
    - /rmfromlist \<items>: to remove  one or several itmes from your personal list
    - /show_list: it shows items that you added to your personal list
    - /clear_list: to delete all items from your pesonal list

- ❓ Message from strangers
    - /topic: to see topic that contains at least one message from a stranger
    - /msg [-user] \<topic> \<text>: to sent a message that everyone can read; -user is optional, if inserted your username will be showed with the message you sent
    - /showmsg \<topic>: to see message about a specific topic
    - /delmsg \<topic>: to delete a your message that you posted in that topic
    - /tagmsg: to check if someone tag you in a topic or message (tag in telegram: @username)
    - /personalmsg: to see all messages you sent

- 🔀 Random value
    - /random \<number>: it will return a random number between 0 and <number>

- ⏰ Alarm
    - /timer \<seconds>: to set a timer and wait for your message
    
- Info about bot
    - /help:  to have info about all commands
    
#### Easter egg

*There are also a lot of easter eggs that the original dev added (you can't find it in this code).
