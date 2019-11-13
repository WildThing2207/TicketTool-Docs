# Change Log
## v4
*2019-10-27*

**Updated Features - Dashboard**
 - Full Dashboard redesign
 - Permissions have been updated with full control like Discord
 - Logging and transcripts have been moved to per panel vs Global
 - Message editors have been update with a full embed editor
 - Automation has been improved and is now enabled
 - Command style tickets / `$new` has been updated to work for each panel
 - The free Ticket message limit has been raised from 40 to 70

**Updated features - Bot**
 - The basic features of the bot have all been updated
 - Transcript has been redesigned to support all messages (embeds,images, etc.)
 - Command style tickets / `$new` has been updated to work for each panel
 - Command `$help` has been updated to include more helpful info (faq/setup)

**New features - Dashboard**
 - A reaction picker has been added for easy reaction selection
 - Custom Commands/Tags have been added for quick responses to tickets
 - New option for your support to claim tickets (Actions taken when claimed is configurable)
 - Logs have been added to the dashboard
 - The option to clone panels has been added
 - Blacklist role added
 - Added the variable `{reason}` to the `$new` command

**New Features - Bot**
 - Tags have been added to allow for quick responses to tickets (set using the dashboard)
 - Commands for claimng added to work with the claim system

**Removed/Replaced Features - Dashboard**
 - Command $panel has been removed and replaced with a sending system using the Dashboard
 - Command $mt/$manageticket has been removed and replaced $add and $remove
**Removed/Replaced Features - Bot**
 - The blacklist command has been removed and replaced with a blacklist role
 - Categories are no longer created automatically (They can still be set under Category Options on the Dashboard)
 - $panel has been removed and replaced with a sending system using the Dashboard
 - Command $mt/$manageticket has been removed and replaced $add and $remove

## 2.1.4 - v4
?> The change log was halted for awhile.

## 2.1.4
*2019-02-20
- Added logging
- Added an option to set the log channel on the dashboard
- Added an option to set what should be logged on the dashboard
- Added an option when creating a panel to override it's name using `$panel <panel name> display:<display name>`

## 2.1.3
*2019-02-09
- Added an option to create panels on the dashboard
- Added an option to reset each panel individuality on the dashboard
- Added an option to delete panels on the dashboard
- Update Panel name now correctly supports Uppercase
- Added new reaction command :tools: (🛠) - ( To Update your panel with the new configuration you can either recreate it using the same name or react to it with :Tools: (🛠) )
- Fixed a random bug with new servers.

## 2.1.2
*2019-02-06*

- Update Dashboard icon inputs to have basic url verification.
- Update Dashboard color inputs to have a color picker & verification.
- Update Dashboard panel settings to use correct nav menu (fixing a bug)
- Update Free message limit from 35 to 40.
- Update $help to use a new format.
- Added $setup for setup and FAQ information.
- Fixed a bug with Using , or . in a ticket name causes them to not be created correct.
- Fixed a bug when having a panel name with symbols would cause itself and other menus to fail on the dashboard.

## 2.1.1
*2019-02-02*

- Update Free users now have a 35 character limit on custom messages.
- Update "Auto Pin Message" is now set per panel under >Other (This is has been reset to defualt "Enabled")
- Update "Ticket Limit" is now set per panel under >Other (This is has been reset to defualt "3")
- Removed  "Auto Pin Message" from General
- Removed  "Ticket Limit" from General
- Added new option under Other "Support Roles" allows you to assign different roles to different panels (same thing can be achived by changing category permissions)

## 2.1.0
*2019-01-30*

- Add new command $manageticket [add/remove] [@user/id] \<#channel/id\>
- Update $transcript to include [limit] option
- Fixed a bug causing new servers to be unable to create panels for this first time.
- Fixed a number of bugs.

## 2.0.9
*2019-01-19*

- Add Link/Unlink to dbvote command
- Update Direct message error response
- Fix Transcripts won't generate without a parent category

## 2.0.8
*2019-01-18*

- Fix Opening a panel with the same name creates a new category
- Fix Using an incorrectly formatted color causing send failed.
- Fix Settings showed saved even when not saved (logged out)

## 2.0.7
*2019-01-17*

- Fix Admin Roles have no effect on bot commands.
- Fix Closing a ticket when auto transcript is enabled doesn't work.

## 2.0.2 - 2.0.6
*2018-12-01 - 2019-01-16*

- Lots of changes/fixes over the holidays that never got tracked.

## 2.0.1
*2018-11-27*

- **Full system rewrite**
- Update changed version code
- Update reaction controls to run faster
- Add a dashboard for managing settings
- Add settings for multiple panels

## 1.0.1.9
*2018-11-10*

- Add $limit to set the open ticket limit per user

## 1.0.1.8
*2018-11-09*

- Fix missing padding on created tickets

## 1.0.1.7
*2018-11-09*
- Update $prefix to $ticketprefix
- Add $prefix to change command prefix

## 1.0.1.6
*2018-11-09*

- Update Tickets now pull any additional permissions from categories when created.(edited)

## 1.0.1.5
*2018-11-09*

- Update transcripts to now use attached files instead of code blocks (formats on saved transcripts to come soon.)
- Update error message for premium commands
- Add permission verification
- Add $invite to show Ticket Tool invite

## 1.0.1.4
*2018-11-07*

- Fix log channel permissions

## 1.0.1.3
*2018-11-05*

- Initial release
