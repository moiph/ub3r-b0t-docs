# FAQ

Below you'll find a list of frequently asked questions, some of which are acceptable, and some of which go against the phrase "there are no stupid questions".

## Does this bot play music?
No, and it will never be added.

## How do I set up Bluesky / Twitch / Picarto / RSS?
See [Notifications](notifications.md)

## The admin panel isn't loading.
Verify you aren't running any extensions that are blocking scripts / network calls, e.g. Privacy Badger.

## Can I self host the bot?
UB3R-B0T's core bot client code is available on [GitHub](https://github.com/moiph/ub3r-b0t). However, portions of the bot are offloaded to separate services so self hosting just the bot will not include most of the commands. It's also not well documented from a dev perspective but you're welcome to explore... :)

## How do I find my server ID?
If the bot is in your server and responding, you can use the `debug` command.
Otherwise: https://cdn.discordapp.com/attachments/178208468124172288/448708933264343040/unknown.png

## Why doesn't this command work? Why isn't the bot responding?
Verify the bot's permissions and roles.  Start with `debug` and make sure that works to verify both read and send permissions.  Make sure you haven't disabled a feature/command in the admin panel.

## How are you?
Splendid. Thanks for assking.

## How do I disable or turn off a command?
Visit the admin settings.

## Where are the admin settings?
jfc just go to the [admin panel](https://ub3r-b0t.com/admin)

## Who are you?
I am UB3R-B0T. Dubmass.

## How do I clear / remove timers?
Use the `timers` command and then `timer remove ID`

## Why is data not showing up for a user for the seen command?
First you need to enable it in the admin panel.  Data is not added retroactively, and syncs periodically.

## How do I stop a user from using the bot?
Create a role called "botless" and assign it to a user to block them from using the bot.

## How does the botless role work?
The botless role blocks a user from using any UB3R-B0T functionality. No extra permissions needed.

## Can I change the bot's avatar / profile picture?
No, avatars are global.

## Can I change teh bot's name?
You can assign a nickname to UB3R-B0T for your own server.

## Who is the bot's voice for greetings and goodbyes?
Play more video games ;)

## How?
https://youtu.be/nAT34iH6xlQ

## Are there hidden commands?
There aren't hidden "commands", but there are a variety of fun responses to undocumented keywords.

## What are fun responses? How can I disable them or some of the silly reactions?
Fun responses are silly responses to undocumented keywords. They can be enabled or disabled in the bot's admin settings.

## Are you a good bot?
you're goddamn right i am

## How do I get the bot to join a voice channel?
Use the `voice` command to have the bot join a voice channel, and the `dvoice` command to leave it.

## How do I set repeating / recurring timers?
You can set daily reminders by setting a timer first, e.g. 'remind me in 24 hours to ', then using the timer number that it gives you (should be several digits) to enter `timer repeat ### daily` or `timer repeat ### weekly` where ### is the timer ID
See the [Commands](commands.md) section for full details.

## How do I add a new template for the meme command?
For the `meme` command you can supply a template ID from imgflip.com to use a meme that isn't in the list.

## How do I let a user manage the bot in the admin panel?
To give a user access to the admin panel, they need to have the Manage Server permission in Discord.

## How do I change the command prefix?
You can change the bot's command prefix in the admin panel.

## I'm getting an error about "shared search limits"
Some commands may return an error message about "Shared search limit reached for the day. Provide your own API key in the admin panel to maintain limits for your own server". These talk to external APIs which require application keys. The default ones used by UB3R-B0T hit their limits very quickly. You need to go to the admin panel and follow the instructions in the commands section to add your own keys.
