AIRTEL MONEY UGANDA — TELEGRAM NOTIFICATION DEMO

IMPORTANT
This is an independent demo, not an official Airtel/Airtel Money website or lender.
The result screen is simulated. No loan is approved and no money is transferred.
The form explicitly asks applicants to consent before sending the listed details
to the site operator through Telegram. Do not collect PINs, passwords or OTPs.

DEPLOY TO VERCEL
1. Extract this ZIP.
2. Upload the contents (index.html, api folder, vercel.json) to a GitHub repository.
3. In Vercel select Add New -> Project and import that repository.
4. Framework Preset: Other. Build Command: leave blank. Output Directory: leave blank.
5. Before deploying, open Project -> Settings -> Environment Variables.
6. Add:
   TELEGRAM_BOT_TOKEN = the token BotFather gave you
   TELEGRAM_CHAT_ID = your numeric Telegram user/chat ID
   Select Production (and Preview if you want test deployments).
7. Save the variables, then go to Deployments and redeploy the latest deployment.

GET YOUR CHAT ID
1. In Telegram open @userinfobot and press Start; copy the numeric Id it shows.
2. Open your own bot (the one created with BotFather) and press Start or send /start.
3. Use the numeric ID from @userinfobot as TELEGRAM_CHAT_ID for a private chat.
4. Never put the bot token in index.html, GitHub source code, or send it to anyone.

TEST
1. Open your deployed Vercel website.
2. Fill the demo form using test details you control.
3. Tick the consent checkbox and submit.
4. The bot should send the test application notification to your Telegram.
5. If it fails, check that the token and chat ID are correct and that you redeployed
   after saving environment variables. Check Vercel -> Functions logs for errors.

The API sends only the form fields shown to applicants after consent. It does not
request or transmit Airtel PINs, passwords, OTPs, identity documents, or bank details.
