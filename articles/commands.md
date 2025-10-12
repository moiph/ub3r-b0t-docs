# The commands

The examples below all assume the bot is using the default command prefix of `.`. That is configurable by server however so mentally swap out with your own server's prefix if applicable.
Or don't, and look like a fool in front of all of your server's peers.

## 8ball
Ask the magical 8ball a question, and get an answer.

Aliases: `8`

`.8ball question` `.8 question`

```html
<arc_> .8ball tell me, do you bleed?
<UB3R-B0T> Only on Tuesdays.
```

## admin
Creates administration settings for the server. (Discord only)

`.admin`

```html
<villzard> .admin
<UB3R-B0T> Manage from https://ub3r-b0t.com/admin
```

## animal
Returns a random animal picture from the assortment of animal commands (cat, dog, bird, etc). Because, animals.

`.animal`

```html
<acoha> .animal
<UB3R-B0T> http://random.dog/20549-24554-21155.jpg
```

## anime
Searches [MyAnimeList.net](https://myanimelist.net) for anime

`.anime anime name`

```html
<wheat> .anime planetes
<UB3R-B0T> Planetes: https://myanimelist.net/anime/329/Planetes | Aired: Oct 4, 2003 to Apr 17, 2004 | Score: 8.40
<moiph> excellent choice.
```

## b
Get the top result from a [Bing](https://bing.com) search.

Aliases: `bing` `img`

`.b search query`

```html
<Mizu> .b odst
<UB3R-B0T> Halo 3: ODST - Wikipedia, the free encyclopedia: http://en.wikipedia.org/wiki/Halo_3:_ODST
<wravey> .b google
<UB3R-B0T> Google: http://www.google.com/
```

## backlog
Gets the most recent items from a user's [backloggery](http://backloggery.com/) profile.

`.backlog username`

```html
<eeeeeee> .backlog moiph
<UB3R-B0T> moiph has most recently played Overwatch | http://backloggery.com/moiph
```

## bear
Returns a random bear from https://and-here-is-my-code.glitch.me/. Because, bears.

`.bear`

```html
<adamjm99> .bear
<UB3R-B0T> https://i.imgur.com/064u3tT.jpg
```

## beer
Searches [BeerAdvocate](http://beeradvocate.com) for beer data.

`.beer beer name`

```html
<ants> .beer Weihenstephaner
<UB3R-B0T> Weihenstephaner Hefeweissbier | Hefeweizen | 5.40% ABV |
Brewed by: Bayerische Staatsbrauerei Weihenstephan (Germany)| BA Score: 98 (world-class)
```

## bgg
Gets info about a board game, from [BoardgameGeek](https://boardgamegeek.com)

`.bgg game name`

```html
<unob> .bgg 7 wonders
<UB3R-B0T> 7 Wonders (2010) | Rank: 36 | Rating: 7.8 | Players: 2 - 7 | Playing time: 30 mins | https://boardgamegeek.com/boardgame/68448/7-wonders
```

## bird
Returns a random bird from http://shibe.online. Because, birds.

Aliases: `birb`

`.bird`

```html
<ak> .bird
<UB3R-B0T> http://cdn.shibe.online/birds/1860ec50c735a5d06462feae203be4cee4d1c6c4.jpg
```

## birthday
Sets your birthday for retrieval or notifications. Currently based off of UTC (i.e. notifications will fire at midnight UTC of your birthday).

Aliases: `bday`

`.birthday | .birthday set dd/mm | .birthday remove | Notifications: .birthday on | .birthday off | .birthday clear`

```html
<don> .bday set 25/12
<UB3R-B0T> Your birthday has been set to December 25 🍰
<don> .bday
<UB3R-B0T>  Your birthday is December 25! patience... 198 days...not even halfway there...
<don> .bday on
<UB3R-B0T> Your birthday notifications have been set for this channel.
```

## cat
Returns a random cat from http://thecatapi.com/. Because, cats.

`.cat`

```html
<xinitrc> .cat
<UB3R-B0T> http://random.cat/i/9DTKzGZ.jpg
```

## choose
Chooses an item from a list. Choices should be separated by commas.

`.choose [--pick:#] item1, item2, ...`  
Provide a `--pick` (e.g. `--pick:3`) if you want multiple options to be selected.

```html
<brain> .choose take over the world, don't take over the world
<UB3R-B0T> take over the world
<pinky> .choose --pick:2 wakko, yakko, dot
<UB3R-B0T> wakko, dot
```

## chuck_norris
Find out 100% true, real facts about Chuck Norris. None of them are fake.

`.chuck_norris`

```html
<luckz> .chuck_norris
<UB3R-B0T> Chuck Norris doesn't need to read command tutorials.  HE
ALREADY KNOWS ALL OF THEM.
```

## clear
Deletes the last X messages from the chat. (Discord only) Use .clear # @username to only clear a single user's messages. Bot cannot delete messages older than 2 weeks (Discord restriction)

`.clear #` `.clear # @username`

```html
<kwoth> .clear 5
-- the last 5 messages, include the .clear command, were deleted --
<khionu> .clear 10 @UB3R-B0T
-- the last 10 messages sent by UB3R-B0T were deleted --
```

## cocktail
Gets cocktail information from http://www.thecocktaildb.com/

`.cocktail cocktail name`

```html
<nair> .cocktail zombie
<UB3R-B0T>
```

## compliment
Get a compliment. (Thanks to http://www.madsci.org/cgi-bin/cgiwrap/~lynn/jardin/SCG)

`.compliment`

```html
<c> .compliment
<UB3R-B0T> As the bile slowly rises in my incandescent eluxulation, your mere presence 
has a calming effect on my rabies.
```

## cowsay
Moo.

`.cowsay text`

```html
<xyz> .cowsay I like to go to the moooovies
<UB3R-B0T>  _______________________________
<UB3R-B0T> < I like to go to the moooovies >
<UB3R-B0T>  -------------------------------
<UB3R-B0T>         \   ^__^
<UB3R-B0T>          \  (oo)\_______
<UB3R-B0T>             (__)\       )\/\
<UB3R-B0T>                 ||----w |
<UB3R-B0T>                 ||     ||
```

## debug
Displays some useful debug info (server/channel IDs, shard info)

`.debug`

```html
<foxbot> .debug
<UB3R-B0T> Server ID: # | Channel ID: # | Your ID: # | Shard ID: #
```

## define
Defines a term, via [Oxford Dictionaries](https://www.oxforddictionaries.com/).

`.define word`

```html
<strawberry> .define beer
<UB3R-B0T> noun: an alcoholic drink made from yeast-fermented malt flavored with hops
```

## dog
Returns a random dog from random.dog. Because, dogs.

`.dog`

```html
<hw> .dog
<UB3R-B0T> http://random.dog/20549-24554-21155.jpg
```

## doesthedogdie
Does the dog die command -- helpful lookup for movies / tv in case you want to avoid media with animal deaths. Because doggies are the best. [Powered by https://www.doesthedogdie.com/](https://www.doesthedogdie.com/)  

Aliases: `dtdd`  

`.dtdd movie`

```html
<spookybird> .dtdd old yeller
<UB3R-B0T> Old Yeller (1957) - Consensus is: **Yes** | https://www.doesthedogdie.com/media/10752
```

## duck
Returns a random duck from https://random-d.uk. Because, ducks.

`.duck`

```html
<birdie> .duck
<UB3R-B0T> https://random-d.uk/api/143.jpg
```

## event
Fetches a random historical event from the day, from Wikipedia

`.event | .event dd/mm`

```html
<arnold> .event
<UB3R-B0T> Random event from 21 of June: 1749 – Halifax, Nova Scotia, is founded. | https://en.wikipedia.org/wiki/Halifax,_Nova_Sco\
tia
```

## expand
Expands a tiny url.

`.expand shorturl`

```html
<CannonFodder> .expand http://is.gd/hDXhSU
<UB3R-B0T> http://ubergaming.net
```

## fact
A random fact. But the source is the internet. So, grain of salt etc.

`.fact`

```html
<zur> .fact
<UB3R-B0T> It's impossible to sneeze with your eyes open.
```

## feedback
Sends feedback about the bot. Ideally, come join the UB3R-B0T server! But if you have a quick comment, send it with .feedback!

`.feedback your feedback here`

```html
<panda> .feedback omfg this bot is pretty bodacioulsy okay
<UB3R-B0T> feeback sent, thx
```

## fc
Get or add friend codes (yay Nintendo online systems)

`.fc [add|remove] [switch|3ds|wiiu|wii|pcamp|pgo] [friend code]` `.fc @user type`

```html
<luthor> .fc add switch 12345
<UB3R-B0T> friend code added
<supes> .fc @luthor switch
<UB3R-B0T> 12345
<bruce> you sure that's a real friend code? I bet it's fake
```

## figlet
Creates large characters made up of ordinary screen characters

`.figlet word`

```html
<voltana> .figlet DOTNET
<UB3R-B0T>  ____   ___ _____ _   _ _____ _____
<UB3R-B0T> |  _ \ / _ \_   _| \ | | ____|_   _|
<UB3R-B0T> | | | | | | || | |  \| |  _|   | |
<UB3R-B0T> | |_| | |_| || | | |\  | |___  | |
<UB3R-B0T> |____/ \___/ |_| |_| \_|_____| |_|
```

## fortune
Gets a fortune from http://yerkee.com.

`.fortune`

```html
<chrissy> .fortune
<UB3R-B0T> The chief cause of problems is solutions. -- Eric Sevareid
```

## fox
Returns a random fox from https://randomfox.ca. Because, foxes.

`.fox`

```html
<xinitrc> .fox
<UB3R-B0T> http://randomfox.ca/images/86.jpg
```

## fm
Get the most recent song a user has listened to (using their [Last.FM](https://last.fm) account) You can also save your account name so that you can just type `.fm`. The `fmyt` variant will include a search for a youtube link for the song.

Aliases: `lastfm`

`.fm username` `.fm set username` `.fm` `.fmyt`

```html
<moiph> .fm
<UB3R-B0T> >> Equilibrium - Dämmerung [Sagas] (Last Played: Equilibrium - Ruf In Den Wind [Sagas])
<moiph> .fmyt
<UB3R-B0T> Equilibrium - Dämmerung - https://youtu.be/nugwSpXjBIE [ 18,789 views | 
5 rating w/ 80 likes (0 dislikes) | Duration: 5m55s | Uploader: Wurzelbert666 ]
```

## fml
Pulls a random quote from http://fmylife.com.
> [!NOTE]
> This command is currently busted. FML shut off their API, so `.fml` is broken until they fix it, someday™

```html
<arc_> .fml
<UB3R-B0T> [#13433715] Today, I gave my two weeks notice at work. My boss sighed with relief and muttered, "Thank God." FML
```

## g
Get the top result from a Google search

`.g search query`

```html
<gamma> .g bing
<UB3R-B0T> https://bing.com
```

## gh
Fetches github data from the commits page of a repo. Not very useful standalone, better in a feeds scenario. Contact moiph if you're interested in pushing commit updates to a channel.

`.gh github repo url`

```html
<moiph> .gh https://github.com/moiph/ub3r-b0t/commits/master
<UB3R-B0T> Adding utilities.cs | Authored by moiph (Dec 31, 2014) | https://github.com/moiph/ub3r-b0t/commit/...
```

## gif
Returns a url for the requested gif (and thus displays it, if in Discord). Results powered by https://tenor.com

`.gif keyword`

```html
<zang> .gif yes
<UB3R-B0T> http://i.imgur.com/sGQWzdz.gif
```

## help
Displays help / URLs, including to this page.

`if you need help using help you are truly lost`

```html
<asmodeus> .halp
<UB3R-B0T> info: https://ub3r-b0t.com | invite: https://ub3r-b0t.com/invite | 
           commands: https://ub3r-b0t.com/commands |
           admin: https://ub3r-b0t.com/admin | patreon: <https://www.patreon.com/ub3rb0t>
```

## hltb
Gets the approximate time to beat a game, from http://howlongtobeat.com

> [!NOTE]
> This command is currently busted. HLTB currently does not provide an API, so `.hltb` is broken until they provide one, someday™

`hltb game name`

```html
<kirk> .hltb Ocarina of time
<UB3R-B0T> 25 Hours  (main story) | 35 Hours  (completionist)
```

## hug
Hugs the target user, or yourself if no target given.

`.hug ` `.hug @user`

```html
<eyuchyu> .hug
<UB3R-B0T> *gives eyuchyu a big kiss unethusiastically*
```


## isup
Checks to see if the given site is up or not.

`.isup url`

```html
<entireties> .isup http://slashdot.org
<UB3R-B0T> http://slashdot.org appears to be up!
```

## imdb
Gets movie info from [IMDB](https://imdb.com)

`.imdb movie name`

```html
<Mizu> .imdb Serenity
<UB3R-B0T> Serenity (2005) (8.0/10 with 99,725 votes)
<UB3R-B0T> The crew of the ship Serenity tries to evade an assassin sent to recapture one of their
           number who is telepathic.
<UB3R-B0T> URL: http://imdb.com/title/tt0379786/
```

## inspire
Get an inspirational message overlayed on an image. Powered by https://inspirobot.me/

`.inspire`

```html
<paulo> .inspire
<UB3R-B0T> https://generated.inspirobot.me/a/rVJqD99gew.jpg
```

## insult
Get an insult, powered by the lovely contents found at https://github.com/jasonlau/jQuery-jlInsults

`.insult username`

```html
<thor> .insult loki
<UB3R-B0T> You are a cruelly loathsome pick pocket and a depraved, 
           armpit-licking offense to all of good taste and decency.
```

## jpeg
Gets more jpeg for an image.

`.jpeg url`

```html
<cbp> .morejpeg
<UB3R-B0T> [PRETEND THERE'S AN IMAGE HERE]
```

## kangaroo
Returns a random kangaroo from https://animality.xyz/. Because, kangaroos.

`.kangaroo`

```html
<phoenix> .kangaroo
<UB3R-B0T> https://cdn.animality.xyz/kangaroo/13.png
```

## kill
No description available (yet)

`.kill username`

```html
<auxesis> .kill finite
<UB3R-B0T> apology for poor english ... when were you when finite dies? i was being rate limited when moiph ring ... "FINITE is kill."   "no"
```

## kiss
Kisses the target user, or yourself if no target given.

`.kiss ` `.kiss @user`

```html
<eyuchyu> .kiss
<UB3R-B0T> *gives eyuchyu and wonders where we take this from here*
```

## koala
Returns a random koala from https://animality.xyz/. Because, koalas.

`.koala`

```html
<syrus> .koala
<UB3R-B0T> https://cdn.animality.xyz/koala/2.png
```

## letterboxd
Pulls user info from [Letterboxd](https://letterboxd.com)

`letterboxd username`

```html
<colonel> .letterboxd colonelmortimer
<UB3R-B0T> Last watched: Mission: Impossible - Fallout (2018) on 2018-07-24 | https://letterboxd.com/colonelmortimer/
```

## lizard
Returns a random lizard from https://some-random-api.ml/. Because, lizards.

`.lizard`

```html
<rukind> .lizard
<UB3R-B0T> https://cdn.nekos.life/lizard/0064.jpg
```

## mal
Gets info from a [MyAnimeList.net](https://myanimelist.net) profile

`.mal username`

## manga
Searches [MyAnimeList.net](https://myanimelist.net) for manga

`.manga manga name`

```html
<wheat> .manga planetes
<UB3R-B0T> Planetes: Planetes: https://myanimelist.net/manga/481/Planetes (1999 - 2004) | Score: 8.36 | Volumes: 4 | Chapters: 27
<moiph> excellent choice.
```

## metal
Searches metal-archives.com for band information.

`.metal band name`

```html
<Z500> .metal Sepultura
<UB3R-B0T> Encyclopaedia Metallum - Sepultura: http://www.metal-archives.com/band.php?id=78
<UB3R-B0T> Genre: [Death/Thrash Metal (early), Groove/Hardcore (later)] Country: [Brazil (Belo Horizonte,
MG)] Year: [1984] Label: [SPV/Steamhammer] Status: [Active]
<Shutdown> .metal spice girls
<UB3R-B0T> No results found. *snicker*
```

## meme
Returns a url for requested meme with the given text (and thus displays it, if in Discord). Use .meme list for a list.

`.meme memename "text line 1" "text line 2"` `.meme list`

```html
<agentorange> .meme paddlin "wastin' time on security?" "that's a paddlin'"
<UB3R-B0T> http://i.imgflip.com/130axx.jpg
```

## mtg
Search for a magic the gathering card, powered by https://scryfall.com/

`.mtg card name`

```html
<evwonder> .mtg black lotus
<UB3R-B0T> Black Lotus | Mana cost: 0 | Artifact | Sacrifice Black Lotus: Add three mana of any one color to your mana pool. 
http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=382866
```

## overwatch
Gets overwatch stats for your player. Data provided through https://github.com/sirdoombox/Overwatch.Net, voice lines from http://http://overwatch.wikia.com.

`.ow username` `.ow username platform`

```html
<apollo> .ow foobar-1234 us
<UB3R-B0T> Level: 32 | Games won: 89/172 (52%) | Most played: Soldier: 76
```

## owl
Returns a random owl from http://pics.floofybot.moe. Because, owls.

`.owl`

```html
<nick> .owl
<UB3R-B0T> https://imgur.com/dOXyeRM
```

## panda
Returns a random panda from https://cdn.animality.xyz/. Because, pandas.

`.panda`

```html
<panda> .panda
<UB3R-B0T> https://cdn.animality.xyz/panda/12.png
```

## patreon
Pulls info for the give patreon user.

`.patreon username`

```html
<fox> .patreon ub3rb0t
<UB3R-B0T> moiph is creating UB3R-B0T
```

## pcspecs
Tells you your PC specs (approximately)

`.pcspecs`

```html
<Atreus> .pcspecs
<UB3R-B0T> CPU: idk lol better not be a 486 | RAM: idk 542 GB? | HDD: idk lol
<UB3R-B0T> OS: idk lol prob windoze | gfx: idk hopefully not onboard lol maybe some nvidia shit
```

## poll
Creates a poll via https://strawpoll.com  
Note: On Discord polls can also be created directly in the client instead of using this command.

`.poll [--multi] "question" "description" | option 1 | option 2 | ...`
Only provide --multi if you want multiple options to be selected in a single vote.

```html
<j> .poll "Is this best poll?" "Well is it?" | Yes | No
<UB3R-B0T> https://strawpoll.com/asdf
```

## quickpoll
Starts a quick poll for a yes or no question, via reactions (discord). Add --options # to use a numbered list instead of yes/no

`.qp yes/no question` `.qp yes/no question --options 4`

![Quick Poll example](~/images/qp.png)

```html
<troos> .qp should we play tf2?
<troos> .qp which tf should we play? --options 3
<troos> lol jk there's no tf3
```

## quote
Get or add quotes for your channel/server.
If you're on Discord, you can react to a message with the 💬 emoji to add a quote.

`.quote` `.quote #` `.quote @nickname` `.quote userid:###` `.quote add "text" - author` `.quote edit # "text" - author` `.quote remove #` `.quote count`

```html
<vision> .quote
<UB3R-B0T> [#33] "I LIVE IN A GIANT BUCKET" - scar
<scar> ugh not that one
<scar> .quote remove 33
<UB3R-B0T> quote removed. laaaaame.
<scar> .quote vision
<UB3R-B0T> [#42] "DATA FOREVER" - vision
```

## raccoon
Returns a random raccoon from https://some-random-api.ml. Because, raccoons.

Aliases: `trashpanda`

`.raccoon`

```html
<panda> .raccoon
<UB3R-B0T> https://i.some-random-api.ml/4cXzHcEMgo.jpg
```

## rant
Rant at the bot. He's a good listener.

`.rant (...whatever is bothering you...)`

```html
<svarrenglossen> .rant fml
<UB3R-B0T> D:
```

## redpanda
Returns a random red panda from https://api.animality.xyz/. Because, red pandas.

`.redpanda`

```html
<helly> .redpanda
<UB3R-B0T> https://cdn.animality.xyz/redpanda/0.png
```

## remove
Removes a timer/warclock/birthday notifications (usage restricted to server admins).
Doing a remove on a 'user' type currently removes all timers associated with that user.
For wc/timer the ID should be the ID of the respective item.
For user/bday the ID should be the user's ID.

`.remove wc #` `.remove timer #` `.remove user #` `.remove bday #`

```html
<ti84ps> .remove wc 1337
<UB3R-B0T> warclock 1337 removed
```

## rep
Reputation command, add or remove reputation for a user to track their goodness.

It's a dark and rainy night. Your car broke down and you just want to get home. You and your friends flag down some help. A mini van full of axe murderers pulls over. You inform them you are just looking for car assistance, not axe murdering. One of them cheerfully chimes in, with a gruff, stern voice: "Lemme axe you a question. Do you need some help? Cause I'm a mechanic". You hesitantly accept. They stagger over and begin inspecting your car's engine. The other axe murderers gaze in your direction with what looks like a thirst for blood. You chuckle to yourself as you remember you have a bunch of red squeeze-its in a cooler in your trunk. Your friends are like "the hell is a squeeze-it". And you're like "get old like me goddamn, they were the shit in the 90s". You pass them out to the axe murderers and it satiates their hunger for axe murdering. Meanwhile the mechanic slaps the hood of your car and exclaims "yeah this bad boy can fit so much kool-aid in it" and you're like "well I got squeeze its" and they're like "well that's cool too, anyway your engine is kickin and ready to axecelerate". You gleefully thank them and decide to use the rep command to show your appreciation. Now anyone else in the server can be like wow that axe murderer is a kind soul when you look past their murderous axeterior.

On discord? You can also use the 🏅 reaction on a message.

`.rep` `.rep @user` `.rep add @user` `.rep remove @user`

```html
<rowetheboat> .rep add @ProtagonistFox
<UB3R-B0T> @rowetheboat gave @ProtagonistFox +1 reputation.
```

## report
Reports a user for misbehavior

`.report username`

```html
<joe4ever> .report anitcb
<UB3R-B0T> ANTITCB HAS BEEN REPORTED TO THE ZONE (MSN GAMING ZONE)
```

## role
Allows a user to self assign a role (or remove it). Configure available roles in the admin panel. (Discord)

`.role rolename` `.derole rolename`

```html
<gamma> .role pwing
<UB3R-B0T> granted access to role pwing
```

If you have Manage Roles permissions, you can also generate a message to allow users to add/remove a role by reactions.
By default the reactions are ➕ and ➖, but can be changed in the admin settings.

`.role generate @role #channel Message text here`

You can replace @role with the roleId if you don't want your message to ping the role. (Or, enable role mentions after setup is done)

## roll
Rolls the dice. Defaults to a 6 sided die but you can supply the # of sides.
`.roll 20` `.roll 6d20` `.roll 20 37 100 42`

```html
<al> .roll 20
<UB3R-B0T> al rolled ... 19
```

## rt
Gets movie info from Rotten Tomatoes.

`.rt movie name`

```html
<Phantom> .rt matrix
<UB3R-B0T> The Matrix (1999): 87% https://www.rottentomatoes.com/m/matrix
```

## seen
Gets the last time the specified user was seen.

`.seen username`

```html
<shade> .seen sun
<UB3R-B0T> sun was last seen on 3/17/2016 1:15AM saying: wut
```

## shibe
Returns a random shibe from http://shibe.online. Because, shibes.

`.shibe`

```html
<bwandyn> .shibe
<UB3R-B0T> http://cdn.shibe.online/shibes/176b62ba761e2949c37a7cd13f88922ef5cc4973.jpg
```

## shorten
Shortens a long url.

`.shorten url`

```html
<Metal_Link> .shorten http://ubergaming.net
<UB3R-B0T> http://is.gd/hDXhSU
```

## spotify
Fetches link / info from spotify for a song. It does not play it. This is not a music bot.

I repeat this is not a music streaming bot.

`.spotify song name`

> [!NOTE]
> This is not a music streaming bot. It does not stream music. It never has and never will.

```html
<zang> .spotify working man
<UB3R-B0T> Rush - Working Man [Rush] https://open.spotify.com/track/1gkn90ExKRNAOlhDs4RoW0
```

> [!IMPORTANT]
> NO MUSIC STREAMING. NEVER

## steam
Returns basic stats from steamcommunity.com for the given user. Note: The username given must be set as a custom URL. If you provide a game acronym (eg tf2) you'll get specific game stats rather than general steam stats.

`.steam custom_url_name` `.steam game name`

```html
<f0rked> .steam f0rked
<UB3R-B0T> SVARRENGLOSSEN XIII: Last Online: 16 days ago | Hours Played [last two weeks]: 0 | Steam
           ID: STEAM:0:1:3266323
<EvilMaverick> .steam tf2 atreus
<UB3R-B0T> Playtime: 70.9 hrs past 2 weeks | Total Points: 134,479 | Most Points: 3,592 (as Medic) | 
           Most Kills: 57 (as Heavy) | Achievements: 202 of 245 (82%) | Fav Class: Medic @ 494.8 hours
<arch> .steam game rocket league
<UB3R-B0T> http://store.steampowered.com/app/252950/
```

## steamnews
Pulls the latest news headline from Steam.

`.steamnews`

```html
<will_> .steamnews
<UB3R-B0T> [Steam News] Now Available on Steam - S.O.R.S - http://store.steampowered.com/news/20704/
```

## stock
Get stock information from https://www.alphavantage.co/

`.stock symbol`

```html
<bucky> .stock gme
<UB3R-B0T> GameStop Corp. (NYSE: GME) | Price: 347.5100 | Open: 354.8300 | Change: 199.5300 | High: 380.0000 | Low: 249.0000 |  Volume: 90516825
```

## summon
Summons a beast of some sort to perform {action}.

`.summon action`

```html
<Speedy> .summon flog moiph mercilessly
<UB3R-B0T> Speedy summons Oeric, the demon of the Forsaken Wasteland to
flog moiph mercilessly.
```

## terminate
Terminates your user data (weather settings, quotes, timers, etc)

`.terminate`

```html
<m89> .terminate
<UB3R-B0T> you have been terminated
```
## time
Gets the current time for you or another user, if a timezone has been set (See [weather](#weather) for location setting)

```html
<bert> .time
<UB3R-B0T> Current time: 17:45 (UTC -07:00:00)
<bert> .time @lewis
<UB3R-B0T> Current time: 00:45 (UTC 0:00:00)
```

## timer
Set a timer, update an existing timer to repeat, gets your current list of reminders, remove a timer, or snooze/unsnooze a recurring timer.

See https://ub3r.bot/reminderhelper to auto-generate a timer command for you.

`hey buttmunch remind [me|someone else] in X [minutes|hours|days|weeks] to Y` `.timer list` `.timer remove ID` `.timer repeat id [xh|daily|weekly|monthly]` `.timer [snooze|unsnooze] id`

```html
<potato> hey buttmonkey remind me in 5 minutes to dance
<UB3R-B0T> Will do, @potato.
--
<egg> .timer list
<UB3R-B0T> 1 timers open. 10626: dance (5m | 4m42s remaining)
<egg> .timer remove 10626
<UB3R-B0T> Timer deleted.
--
<greenpepper> hey jerkward remind me at 17:35 -7 on 2017/05/04 that it's may the 4th be with you day
<UB3R-B0T> Consider it done, @greenpepper.
--
<cheese> .timer repeat 10735 daily
<UB3R-B0T> Timer updated to repeat daily.
--
<mushroom> .timer repeat 7513 5h
<UB3R-B0T> Timer updated to repeat every 5 hours.
--
<tomato> .timer snooze 5174
<UB3R-B0T> Timer snoozed.
```

Setting a timer to 'snooze' will suppress it from sending a notification, and only applies to recurring timers. Unsnoozing will resume it.

## tumblr
Pulls a tumblr user's last post and links to their blog.

`.tumblr username`

```html
<theking> .tumblr wendys
<UB3R-B0T> WENDY'S | https://wendys.tumblr.com/post/78445640171 | https://wendys.tumblr.com/
```

## title
Retrieves the title of the last URL seen in the channel (or the provided URL, if one is specified)

`.title` `.title url`

```html
<windeh> http://www.coopext.colostate.edu/4DMG/Pests/flyant.htm
<MirrorImage> .title
<UB3R-B0T> On Flying Ants
<eric-sad> I don't like ants :(
```
## track
Tracks packages! Works with FedEx, DHL, Ontrac, UPS, and USPS packages too! To see packages you're currently tracking, type .track list.

`.track [carrier] ### [description]` `.track list` `.track remove`

```html
<Robo_Leader> .track ups 1ZY232580398906846
<UB3R-B0T> Now tracking 1ZY232580398906846 for Robo_Leader
...
<UB3R-B0T> oshi- Robo_Leader, an upsdate!
<UB3R-B0T> Status: In Transit - On Time | Scheduled Delivery: 10/02/2009 | Location:  ROSEBURG OR US  
           @ 09/30/2009 12:47 P.M. for DEPARTURE SCAN
<Lummeh> .track list
<UB3R-B0T> Currently tracking: 1Z3X295R0393256158 005794585637304
...
<Lummeh> yo UB3R-B0T where are my packages
<UB3R-B0T> Status: In Transit | Scheduled Delivery: 10/03/2009 | Location: ADDISON IL US
           @ 10/1/2009 3:43 P.M. for ARRIVAL SCAN
```

## trakt
Gets a user's recently watched content from https://trakt.tv

```html
<asci> .trakt
<UB3R-B0T> >> Last watched: a thing
```

## translate
Translates text. From a language to another language. Supported languages: ar, bg, ca, cs, da, de, el, en, es, et, fa, fi, fr, he, hi, ht, hu, id, it, ja, ko, lt, lv, ms, mww, nl, no, pl, pt, ro, ru, sk, sl, sv, th, tr, uk, ur, vi, zh-chs, zh-cht

Aliases: `tr`

`.translate language text` [Note: language is the ISO code e.g. es, fr, de, etc

```html
<shades> .translate es help me I have lost my shoes
<UB3R-B0T> ayuda me he perdido mis zapatos
```

## trello
Grabs the current Trello board for task tracking. Vote on the cards important to you!

`.trello`

```html
<zurk> .trello
<UB3R-B0T> https://trello.com/b/zbELOMit/ub3r-b0t
```

## twitter
Retrieves the latest update for the given user.

`.twitter username`

```html
<Drullexx> .twitter UB3RB0T
<UB3R-B0T> LOLOLOLOLOL | 5h
```

## ud
Gets a definition of a word/phrase from [Urban Dictionary](https://urbandictionary.com)

`.ud word`

```html
<svarrenglossen> .ud Patrick
<UB3R-B0T> All around perfect man and a sexy beast. Known to cause even the most loyal of girls to
           turn on their boyfriends. Talented with music, words, and kills in any sport he plays.
           Strong like bull. Always competitive, and ALWAYS wins what he competes in. Some consider to
           be on the status of not only a god, but THE God.
```

## ups
Deprecated; use the `track` command instead

## uptime
Gets the bot's current uptime.

`.usage`

```html
<zang> .uptime
<UB3R-B0T> 7 days, 3 hours.
```

## userinfo
Displays some general info about the user (joined date, avatar, etc). Discord only.

```html
<bucky> .userinfo 
<UB3R-B0T> bucky#1337 {
    id: "1234567891223",
    nickname: "",
    avatar: "https://linktoavatar",
}
```

## vblk
Vibe links. Supply a phrase (perhaps relevant to current conversation) to generate a vibe link which redirects to a buest guess desintation. [Powered by https://vb.lk/](https://vb.lk/)

```html
<ms> .vblk always has been
<UB3R-B0T> https://vb.lk/always-has-been
```

## votekick
Starts a votekick

`.votekick user`

```html
<eeeeeeee> .votekick moiph
<UB3R-B0T> VOTING INITIATED...OVERRULED VOTE HAS PASSED
```

## voice
Adds the bot to the voice channel you're connected to (Discord). Use .dvoice to have him disconnect.

`.voice` `.dvoice`

```html
<ikarus> .voice
<ikarus> lol now he's greeting people when they join the voice channel
--
<ikaraus> ok that's enough of that for now
<ikaraus> .dvoice
```

## weather
Check the local weather! You can also save your location so that you don't need to provide a location every time. The other variants (fw/sw/nw etc) give weather data back in other, arguably more fun, ways... [Powered by OpenWeather](https://openweathermap.org/)

Additionally, you can allow others to lookup your weather via `set public`.  
To restrict, use `set private`. 
Or to clear your location entirely, use `clear` or `remove`

Aliases: `w` `sw` `fw` `nw`

```html
<moiph> .w 61820
<UB3R-B0T> Mostly Cloudy, 10F (-12C) (261.15K) / feels like 1F (-17C) (256.15K) |
           Humidity: 76% | 0% chance of precipitation (61820 - Champaign, IL (US) as of 12:21 am UTC)
<apples> .w set boston, ma
<UB3R-B0T> location saved.
<apples> .w
<UB3R-B0T> Partly Cloudy, 24F (-4C) (269.15K) / feels like 21F (-6C) (267.15K) |
           Humidity: 64% | 0% chance of precipitation (Boston, Massachusetts (US) as of 12:22 am UTC)
```

```html
<moiph> .w @apples
<UB3R-B0T> nope
<apples> .w set public
<UB3R-B0T> Other users can now check your weather.
<moiph> .w @apples
<UB3R-B0T> Partly Cloudy, 24F (-4C) (269.15K) / feels like 21F (-6C) (267.15K) |
           Humidity: 64% | 0% chance of precipitation (Boston, Massachusetts (US) as of 12:22 am UTC)
```

```html
<apples> .w clear
<UB3R-B0T> Your weather location has been removed
```

## wc
Creates a clock to track how much time has passed since a particular event.

`.wc #id` `.wc list` `.wc start text` `.wc stop #id` `.wc reset #id`

```html
<cbp> .wc start time since moiph created warclock command
<UB3R-B0T> warclock added as id #1337
<cbp> .wc stop 5
<UB3R-B0T> warclock deleted.
<cbp> .wc list
<UB3R-B0T> (#1337) time since moiph created warclock command: 7 years, 4 months, 3 days,  1 hour
<cbp> .wc reset 1337
<UB3R-B0T> warclock reset.
<cbp> .wc 1337
<UB3R-B0T> (#1337) time since moiph created warclock command: 30 seconds
```

## whale
Returns a random whale from https://cdn.animality.xyz/. Because, whales.

`.whale`

```html
<wine> .whale
<UB3R-B0T> https://cdn.animality.xyz/whale/8.png
```

## wiki
Fetches the first result from Wikipedia.

`.wiki keywords`

```html
<tyler> .wiki paper cut
<UB3R-B0T> A paper cut occurs when a piece of paper or other thin, sharp material slices a person's skin.
           Paper cuts, though named from paper, can also be caused by other thin, stiff materials.
           https://en.wikipedia.org/wiki/Paper_cut
```

## wolfram
Queries the Wolfram API for results on...anything! Instead of .wolfram you can also say "UB3R-B0T tell me [question]"

`.wolfram query`

```html
<erasmus> .wolfram population of Kansas City MO
<UB3R-B0T> 451572 people  (country rank: 39th)  (2008 estimate)
<PaperCut> UB3R-B0T tell me the population of the moon
<UB3R-B0T> Extraterrestrial Life: Development of this topic is under investigation...
```

## woot
Displays the latest item from woot!

`.woot`

```html
<SlayerGhede> .woot
<UB3R-B0T> woot-off! Acer Aspire One 10.1" Netbook going for $229.99 + $5 shipping is available! [====      ] (41%)
```

## xkcd
Fetches the latest / a random / a specific XKCD comic.

`.xkcd` `.xkcd random` `.xkcd ###`
```html
<oss> .xkcd
<UB3R-B0T> [latest xkcd comic]
```

## yt
Searches youtube and returns the first result.

`.yt query`

```html
<Slash> .yt bunnies
<UB2R-B0T> Soft, cuddly bunny: https://youtube.com/watch?v=pn9oufznHrQ
<Slash> omg awwwww <3
```
