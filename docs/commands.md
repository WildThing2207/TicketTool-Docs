# Commands
Optional=`{}`  
Required=`[]`

### Settings
All settings are configured using the [Dashboard](https://tickettool.xyz/dashboard).

##  Tickets/Panel

| Command | Usage | Aliases | Desc |
| :---------- | :-----------: | :-----------:| :------------------------------ |
| Panel | $panel [panel name] | tt,ticket | Creates ticket panel or recalls panel created online |
| Clean | $clean {close/delete} {seconds} {panel name} | none | Closes or deletes all open tickets that haven't recieved a response in X seconds. (Specify "s, m, h, d" in time to use different unit of time |
| New | $new | none | Creates a new ticket using a command rather than a reaction on the panel |
| Rename | $rename [new ticket name] | none | Renames a ticket's channel name |
| Setup | $setup | none | Sends a message with brief setup information and FAQ |
| Manage Ticket | $manageticket [add/remove] [@user/id] {#channel/id} | mt | Adds or removes a user from a channel |
| Delete | $delete | none | Deletes the ticket bypassing closing and the mod menu |
| Close | $close | none | Closes an open ticket via command instantly |
| Open | $open | none | Reopens a closed ticket instantly bypassing the Mod Menu |

##  System

| Command | Usage | Desc |
| :---------- | :-----------: | :------------------------------ |
| Transcript | $transcript {limit} | Creates a transcript of the last x messages in channel (Default: 1000)|
| Help | $help {command} | Displayes this list in an embed |
| Blacklist | $blacklist [@user/id] {add/remove} | Prevents a member from creating any tickets on the deployed server |

?> When using the blacklist command, users will be added to the blacklist unless otherwise defined in the command.

##  Miscellaneous

| Command | Usage | Desc |
| :---------- | :-----------: | :------------------------------ |
| Vote | $vote | Allows a user to earn premium time by voting for Ticket Tool on [DiscordBots.com](https://discordbots.org/bot/557628352828014614/vote) |
| Debug | $debug | This will list the permissions (This command will commonly be used under the request of a support represenative) |
| Ping | $ping | Checks Ticket Tool's response time |
| PermLevel | $permlevel | Shows you your server permission level |

?> When the Vote command is linked, a users vote count will be transfered to the user linked to.
