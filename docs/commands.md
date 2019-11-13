# Commands
Ticket Tool offers several commands to help you manage tickets.

>() = optional  
>[] = required  
> Default prefix is `$` Yours may be different  
> 💎 = Premium only command

> `user` parameter can be a mentioned user or their ID  
> `command` parameter can be mentioned or its ID

## Ticket Commands
### `$add [user] (channel)` - Add user to a ticket

![add command](_media/add.png)

### `$remove [user] (channel)` - Remove user from a ticket

![remove command](_media/remove.png)

### `$close` - Close a ticket

Must be run in the ticket channel.

![close command](_media/close.png)

### `$open` - Reopen a ticket

Must be run in the ticket channel.

![open command](_media/open.png)

### `$delete` - Delete a ticket

Must be run in the ticket channel.

![delete command](_media/delete.png)

### `$rename` - Rename a ticket channel

Must be run in the ticket channel.

![rename command](_media/rename.png)

### `$transcript (channel)` - Sends a transcript to optional channel

If omitted, transcript will be sent to current channel.  

![transcript command](_media/transcript.png)

### `$new (user) (reason)` - Create a new ticket

!> **[Command Style Tickets]() must be enabled!**

**`{reason}` must be included in the ticket's creation message to have an effect**

![new command](_media/new.png)

### `$claim` 💎 - Marks a ticket as claimed, or unclaimed

*Alias: `$unclaim`*

![claim command](_media/claim.png)

## Utility Commands
### `$help (topic)` - Shows help topics

Include topic name for more help.

![help command](_media/help.png)

### `$debug` - Sends a DM with the bot's permissions, prefix, shard and ping

*Alias:* `@Ticket Tool#4843 debug`

![debug command](_media/debug.png)

### `$id (@role | @user | #channel | emoji)` - Translate a mention/emoji into its ID

![id command](_media/id.png)

### `$ping` - Pong. Measure the bot's latency in your server

![ping command](_media/ping.png)

### `$permlevel` - Display your permission level of the bot

*Alias: `$level`*

![permlevel command](_media/permlevel.png)

### `$vote (link | unlink | redeem) (user)` - Vote for the bot!

**Linking**  
You can give your future votes to another user by linking with that user.

To link use `$vote link (@user or userId)`

To unlink use `$vote unlink`


**Redeeming**  
Each vote is worth 12 hours of premium and can be redeemed once you have at least 6 votes.

To redeem your votes, use `$vote redeem`

!> Only redeem in your _own_ server!

![vote command](_media/vote.png)