# Command: import
---
### Description
Use this command to import suggestions from both regular users and [supported bots](admin/import.md?id=supported-bots) into Suggester's database, allowing you to manage them using our tech. If you choose to import messages from a channel, Suggester will count any message as a suggestion. Make sure to remove unwanted messages before processing!\
Messages can only be added to the database **once**, re-using the command will not import the same suggestion twice, even if you delete it. 

### Usage
Use `.import (message override)` in a channel with suggestions or messages you'd like to import

### Arguments
`message override`: The number of past suggestions you'd like to import (optional, 30 by default, 30 maximum per-command) 

!> If you need to import more than 30 suggestions **at once**, please contact our [Support Team](https://suggester.js.org/support). The limit is 30 suggestions **per-command**, which means if you need to import 60 suggestions, you'll need to run the command twice (30 x 2 = 60). Our support team can give you an override if you need to import a lot of suggestions at once (read multiple hundreds)

### Permissions
To execute this command, the user must have the **Manage Server** permission or a configured [admin](/config/adminroles.md) role

!> If it doesn't work, make sure Suggester has the **Read Message History** permission in the channel you're trying to use the command in.

### Supported Bots
Suggester currently supports importing suggestions from the following bots:

- ,Havoc#7078
- AXVin#4169
- Anchor#8635
- Carl-bot#1536
- Fast Bot.#2211
- Gaius Cicereius#3705 
- Juzo#2390
- Kashima#4514
- Suggestion#2670
- Suggestions#2602
- Suggestions#3153
- Suggestions#6994
- Ticks#3610
- UnbelievaBoat#1046
- UnbelievaBoat Premium#3539
- Zira#9472 

?> You're using a suggestion bot that's not listed above and you want to switch to Suggester? Head over to our [support server](https://suggester.js.org/support) and tell us! We want to support importing from as much bots as we can, but we might have missed a few :(


