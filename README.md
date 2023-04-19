# tg_bot_sqlite
<div id="header" align="center">
  <img src="https://media.tenor.com/QTc7sR9KDNYAAAAi/cherry-hi.gif" width="200"/>
</div>
<div id="badges" align="center">
<h1>
 Hello there
  <img src="https://media.tenor.com/znmQl_Of2AAAAAAi/pepe-jedi-pablojedi.gif" width="50px"/>
</h1>
</div>

This code is a Python script that uses the Telebot library to create a Telegram bot that registers users and stores their information in an SQLite database.

The bot is created using a token provided by Telegram, which is used to authenticate the bot with the Telegram API. When the bot receives the '/start' command from a user, it creates a new table in the SQLite database (if it doesn't exist already) and prompts the user to enter their name.

Once the user enters their name, the bot stores the name in a global variable and prompts the user to enter their password. When the user enters their password, the bot inserts the user's name and password into the 'USERS' table of the SQLite database.

The bot also creates an inline keyboard with a button that, when clicked, retrieves a list of all registered users from the database and sends it back to the user.

The bot continuously polls the Telegram API for new messages and callbacks, and responds to them accordingly.


