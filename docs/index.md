---
layout: default
---

[Niles](http://seanecoffey.github.io/Niles) is a Discord bot for interfacing with Google Calendar.

## Niles can help you if...

* You want to create a single channel to manage events in your Discord server.
* You want to sync events from ([Google Calendar](https://calendar.google.com)).

This page itself is built with Solo. It's generated from [this markdown file](https://github.com/chibicode/solo/blob/gh-pages/_includes/index.md).

## Setup

First [invite Niles](https://discordapp.com/oauth2/authorize?client_id=320434122344366082&scope=bot&permissions=523344) to your Discord server.
Next either create a new Google calendar or use an existing one, and under **Settings > Calendars > 'Calendar Name'**, select 'Share This Calendar' and under 'Share with a specific person' add `niles-291@niles-169605.iam.gserviceaccount.com`.

Next head to 'Calendar details' and copy the **Calendar ID** - We'll use this when we setup Niles in your Discord Server.
Run `!setup` in your `#general` to get started.

## Usage

### Commands

* `!help`     - Get a DM of the list of commands and usage.
* `!setup`    - Get instructions for setting Niles up for use in your Discord.
* `!id`       - Set the Google Calendar ID for the calendar you want Niles to sync to.
* `!tz`       - Set the preferred timezone of your Discord server, use format relative to GMT:`!tz GMT+10:00`
* `!init`     - Cleans messages from the current channel (all) and displays a calendar message.
* `!display`  - Prints a message with the calendar.
* `!update`   - Checks for any new events and updates the last printed calendar, also works as `!sync`.
* `!create`   - Create a new event: `!create 4legs friday 8pm-10pm`, also works with `!scrim`.
* `!delete`   - Delete an event: `!delete <day> <start time>`, i.e. `!delete friday 8pm`.
* `!clean`    - Deletes all messages in the current channel, also works as `!purge`.
* `!invite`   - Get the invite link for the Niles.
* `!stats`    - Display the stats for the bot.
* `!ping`     - Pong!
* `README.md` before pushing your code.

## Support

Join the [Niles Discord server](https://discord.gg/jNyntBn) if you have issues or suggestions.

## Author

Sean Coffey ([GitHub](http://github.com/seanecoffey)).

![Sean Coffey](https://static1.squarespace.com/static/5114c744e4b044f8ed62c985/t/57bd4b01f7e0ab7f8047e458/1485628111532/?format=500w?s=200)

### License

[MIT License](http://seanecoffey.mit-license.org/)