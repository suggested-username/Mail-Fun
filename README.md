# Mail-Fun-EU

QoL tbh 

Mod By: Cattalol + NotZiora

Modification of Region: suggested-username

## Setup:
- Place all .def files in the defs folder inside `<path to proxy>\node_modules\tera-data\protocol\` (there will be lots of other .def files already inside)
- Add following map to node_modules\tera-data\map\protocol.365098.map<br>
C_SET_SEND_PARCEL_TYPE = 39286<br>
C_SET_SEND_PARCEL_MONEY = 44658<br>
C_SEND_PARCEL = 49660<br>
S_INVEN = 38369<br>

## Usage:
- This module will proceed to ~~spam~~ meme a target character's parcel-post with **creative and totally inoffensive** messages. 
Each message is attached with 1 (one) copper each, so the recipient may not batch-delete them using "normal" methods.
- You will need up to 51 Silver (51 Copper x 100) for each meme session.
- Find someone you like ~~or hate~~, and let the memes begin!
- Modify the entries in config.json according to your uh... _**preferences**_. A random subject header and message will be drawn from the lists on each parcel post.

## Commands (in the proxy channel):
### mememail [target character name]
- Proceeds to meme the target's inbox, up to 100 (their inbox can hold up to 100 player-sent parcels (system messages do not count towards this limit).
### mememailnum [number]
- Set the maximum number of parcels to send (note: will not exceed target inbox capacity of 100, or other game related restrictions).
### mememailstop
- Interrupts the mailing procedure.
