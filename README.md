# Feature-list for Nia#3208  

## Moderation

### ban

Example: `&ban [user mention] [reason for audit logs]`  

This command bans the [user mentioned] with [reason for audit logs]

### kick

Example: `&kick [user mention] [reason for audit logs]`  

This command kicks the [user mentioned] with [reason for audit logs]

### nick

Example: `&nick [user mention] [new nickname]`

This command sets the [user mention]'s nickname as [new nickname]

### profanity

Example: `&profanity`

This command enables the profanity filter in the server

### purge

Example: `&purge [integer between 1-100]`

This command deletes [integer between 1-100] messages in current channel

### vcdeaf

Example: `&vcdeaf [user mention] [reason for audit logs]`

Voice deafens the [user mention] server-wide for [reason for audit logs]

### vckick

Example: `&vckick [user mention] [reason for audit logs]`

Voicekicks the [user mention] for [reason for audit logs]

### vcmute

Example: `&vcmute [user mention] [reason for audit logs]`

Voice mutes the [user mention] server-wide for [reason for audit logs]

### vcundeaf

Example: `&vcundeaf [user mention] [reason for audit logs]`

Voice un-deafens the [user mention] server-wide for [reason for audit logs]

### vcunmute

Example: `&vcunmute [user mention] [reason for audit logs]`

Voice un-mutes the [user mention] server-wide for [reason for audit logs]

### warn

Example: `&warn [user mention] [reason]`

Bot warns the [user mention] in DMs for [reason]

## Music  

### clearqueue

Example: `&clearqueue`

This command clears the Music queue for the server (If it exists)

### disable-repeat

Example: `&disable-repeat`

This command stops looping the current song being played (If it exists)

### enable-repeat

Example: `&enable-repeat`

This command starts looping the current song being played (If it exists)

### np

Example: `&np`

Bot responds with the name of currenly playing song (If it exists)

### pause

Example: `&pause`

This command pauses the current queue (If it exists)

### play

Example: `&play [song name or url]`

This command plays the [song name or url] in vc

### queue

Example: `&queue`

Bot responds the the current server queue (If it exists)

### resume

Example: `&resume`

This command resumes the current queue (If it exists)

### setvolume

Example: `&setvolume [integer 0-10]`

Sets the volume of current queue to [integer 0-10] (If it exists)

### skip

Example: `&skip`

Skips one song from queue (If it exists)

### stop

Example: `&stop`

This command stops the current queue (If it exists)

## Giveaways

### end-giveaway

Example: `&end-giveaway [message id]`

This command ends the giveaway with [message id]  

### reroll-giveaway

Example: `&reroll-giveaway [message id]`

This command rerolls the giveaway with [message id]  

### start-giveaway

Example: `&start-giveaway [channel mention] [duration] [winners] [prize]`

This command creates a giveaway in [channel mention] for a duration of [duration] and for [winners] winners and [prize]

## Images  

### Commands which require 1 users as a mention

3000years, amiajoke, approved, av, avatarlink, beautiful,  

brazzers, captcha, crush, dictator, fire, frame, glitch,  

jail, look, passed, pixelize, rejected, rip, scary, steam,  

tbc, thanos, threats, triggered, trinity, wanted, wasted  

### Commands which require 2 users as a mention

afusion, vs, www

### Special image commands

cat

Example: `&cat`

Generates a cat image

dog

Example: `&dog`

Generates a dog image

clyde

Example: `&clyde [some text]`

Generates clyde image with [some text]

scroll

Example: `&scroll [some text]`

Generates scroll image with [some text]

## Others

### afk

Example: `&afk [afk note]`  

This command sets you as AFK and when you are pinged in the chat, bot responds with your [afk note]

### changelog

Example: `&changelog`  

This command displays the recent changes made to the bot  

### chat

Example: `&chat [chat arguments]`  

Bot chats with you according to the [chat arguments] provided

### help

Example: `&help`

Bot responds with command categories

### invite

Example: `&invite`

Bot responds with bot's invite link

### setlanguage

Example: `&setlanguage [params]`

Possible value for [params]: french or english

sets the [params] as the bot's language for the server

### ping

Example: `&ping`

Bot responds with the Roundtrip and bot latency

### poll

Example: `&poll [poll arguments (min: 2, max: 10)]`

Creates a poll in the channel with [poll arguments (min: 2, max: 10)]

### prefix

Example: `&prefix [new prefix]`

This command sets [new prefix] as the server's prefix

### resetprefix

Example: `&resetprefix`

Resets the server prefix to default (no matter what current prefix is running `&resetprefix` will reset your prefix to default)

### say

Example: `&say [some text]`

Messages the current channel with [some text]

### server

Example: `&server`

Bot responds with the server information

### snipe

Example: `&snipe [channel mention]`

Bot responds with the last message deleted in [channel mention]

### stats

Example: `&stats`

Bot responds with system stats

### support

Example: `&support`

Bot responds with support related information

### uptime

Example: `&uptime`

Bot responds with bot's uptime

### urban **(NSFW)**

Example: `&urban [some word to search]`

Bot performs a search for [some word to search] on urban dictonary and returns the response

### vote

Example: `&vote`

Bot responds with bot's top.gg vote link

### whois

Example: `&whois [user mention]`

Bot responds with details of [user mention]
