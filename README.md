# Vote Bot

---

Discord Bot written in Python with [discord.py](https://discordpy.readthedocs.io/en/latest/)


## Simple voting features like:
 - Create poll without answers
 - Create poll with answers
 - End a poll (Through command and reaction)

## Commands

| Name | Usage | Description (Click to see full details)
| --- | --- | --- |
| vote | <code>p?vote \<question> {answers}</code> | <details><summary>Create a poll</summary>If {answers} is not specified, a YES or No vote will be taken, otherwise, the specified responses will be used.</details> |
| endvote | <code>p?endvote \<message id></code> | <details><summary>Ends a poll by passing the message ID</summary>You can also end a poll just by reacting with :stop_button: in the poll message.</details> |
| help | <code>p?help {command}</code> | <details><summary>The help command for the help command</summary>If {command} is specified, it will show the detailed help for that command.</details> |
| bug | <code>p?bug \<report></code> | <details><summary>Report a bug</summary>There is a 30-second cooldown</details> |
| suggestion | <code>p?suggestion \<suggestion></code> | <details><summary>Send a suggestion or idea you have that could be interesting for the bot</summary></details> |