# XKols-TwitterAutoBot
NodeJs X (Twitter) Bot that automates several actions on Twitter, such as view, like, following users and share comments.

WORK ONLY ON WINDOWS 10,11 64bit. 
TOOL FREE AND DO NOT REQUIRE ANY PERMISSIONs FROM YOUR ACCOUNT.

**HOW IT WORKS**
- Register an account on XKOLS Network https://xkols.com, each account on XKOLS network must be matched with username account on X (Twitter).
Eg: Your twitter acccount is: https://twitter.com/exampleusername, so the usename on XKOLS you have to register is: exampleusername.
- We will exchange all the actions on every X account to points: 1 view = 1 point, 1 like = 1 pont, 1 retweet = 2 ponts, 1 comment = 5 points.
- When you run bot tool, the Browser will open and auto view, likes, follow all the others accounts from XKOLS network. More time to run bot more points you can earn.
- When you comment, like, share other tweet you will plus points. Otherwise, You will be deducted points (when other people interacted with your tweet).
- Our system will crawl your tweets every minute and push them to the GOLDEN TABLE, you will have max 100 SLOTS on the GOLDEN TABLE TO INTERACT.

**INSTALL LIBRARY**
- Step 1: Go to link: https://nodejs.org/en/download/ then download NodeJS Application.
- Step 2: Open downloaded file, double click to start installing NodeJS.

**INSALL APPLICATION**:
- Checkout source code XKols-TwitterAutoBot
- Step 1: Click INSTALL_CLIENT_APP.bat to install all libraries and wait until finish, the terminal will close automatically.
- Step 2: Rename file config.json.example to config.json, go to line: X_USERNAME: "X_ACCOUNT", replace your X (Twitter) account X_ACCOUNT by username of X (Twitter). Eg: your twitter acccount is: https://twitter.com/exampleusername, so you have to edit line 08: "X_USERNAME": "exampleusername".
- Step 3: Click file START_CLIENT_APP.bat to run app, you will see a black screen (terminal), do not stop terminal when running auto bot.

**NOTE**:
- You MUST use English from Twitter account, we do not support others languages. (Login to X account > More > Settings and Support >Accessibility, display and languages > Languages > Display language then select English).
- For the first time, the application will open Chromnium for you to login Twitter account, you have to login. After loggged in (navigated to home), close Chromnium browser + terminal START_CLIENT_APP.bat then start START_CLIENT_APP.bat again.
- From 2nd time, you only need to run START_CLIENT_APP.bat, and do not need to re-do any steps above.
- When you need to close app, press Ctrl + C, the message: "Terminate batch job (Y/N)?" will appear, type "y" > Enter to close.

**Q&A**
- Q: How many way to earn points?
- A: 
- Tip 1: You can earn point by open XKOLS_TOOLS.BAT and auto view, like for other tweet, The longer you run the tool, the more points you earn.
- Tip 2: Use your affiate link to share with your friend to earn point.  
- Tip 3: Go to the GOLDEN TABLE (Most important) to interact with other members on XKOLS NETWORK to enhance engagement point.
- Q: How can I find my activity history?
- A: Check: https://xkols.com/network-activities/

**AUTO FEATURES**

- Tool will run auto view/like all off links from GOLDEN TABLE.
- Tool will run auto follow all of user account has GREEN TICK.
- Tool will run auto every 5 minutes.
- Note: 
You can open background task by edit from config file by update: BROWSER_UI_MODE: 1 to 0. (Eg: BROWSER_UI_MODE: 0)
If from terminal, appear message "PLEASE LOGIN AGAIN", that means your cookies expired. You have to disable backgound task (edit file config.json, change BROWSER_UI_MODE: 1) to login again, after that restart tool more time.

- Watch video How to use: https://drive.google.com/drive/folders/13CasG0ro5atqTwz4phimNOrw0O29qylJ
- Telegram & Support: https://t.me/x_connectvn