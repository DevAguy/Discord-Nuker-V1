This is DevAguy's Discord Nuke V1

Commands:
*TO ADD THE BOT YOU MUST HAVE THE MANAGE SERVER PERMISSION*

1) !nuke 
> Tries to delete all server channels.
- Requires the 'Manage Channels' Permission.


2) !spam 'number of channels' 'channel_name'
> Creates the specified number of channels with the given name. 
- Requires the 'Manage Channels' Permission.
- !spam defaults = 10, 'get spammed'

	EXAMPLE:
!spam 100 "Hacker by Admin" (creates 100 channels named 'subscribe')
!spam (creates 10 channels named 'get-spammed')


3) !ban 'target'
> Bans a given member or if not specified, bans everyone possible.
- Requires the 'Ban Members' Permission.
- You can only ban members with a role lower than the bot.

	EXAMPLE:
!ban "ExampleUser" (tries to ban member with the name 'ExampleUser123')
!ban (bans everyone possible)


4) !kick 'target'
> Clone of !ban but kicks instead of banning the member.
- Requires the 'Kick Members' Permission.
- You can only kick members with a role lower than the bot.

	EXAMPLE:
!kick "." (tries to kick member with the name 'ExampleUser123')
!kick (kicks everyone possible)


5) !droles
> Tries to delete all roles.
- Requires the 'Manage Roles' Permission.


6) !sroles 'number of roles' 'role_name'
> Creates the specified number of roles called the given name.
- Clone of !spam just with roles.
- Requires the 'Manage Roles' Permission.
- !sroles defaults = 10, 'spam'

	EXAMPLE:
!sroles 100 "subscribe" (creates 100 roles named 'subscribe')
!sroles (creates 10 roles named 'spam')


7) !alert 'message' 'time_spamming (how many seconds)'
> Spams the given message for the specified time.
- Requires the 'Send Messages' Permission.
- !alert defaults = '@everyone', 10

	EXAMPLE:
!alert "Clowns" 12 (spams the message "Make sure to Boost to @" for 12 seconds)
!alert (spams the message '@everyone' for 10 seconds)


~ DevAguy#3721
