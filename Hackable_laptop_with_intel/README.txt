# hackable laptop with intel
- laptop has a hold action to "hack" it
- all players that have the attribute "isHacker" set, can use the action (see the left unit inits field)
- once the laptop is hacked, the synced trigger is executed
- for show purposes, the trigger unlocks a briefing entry in the map, and uncovers a yellow USB drive on the table
- during the hacking process, the slicer-player is shown "technical" information as silenthint for immersion

## customize
- you can copy/paste the laptop and sync it to the same trigger. both laptops can now execute the hack.
- you can use the composition more than once in your mission, they are independent to eachother.
- only the trigger and laptop are relevant for the system. the breifing entry, show-object system and thumbdrive can be safely deleted.
- if you have multiple laptops to execute the hack, the other laptops will still show the "hack me" action even though the hack is already complete.
- only units that have the variable "isHacker" set to true for them (ideally globally) can use/ can see the hold-action. also if they are zeus controlled.
- to create more slicers, copy-paste the code from the slicers "init" field. dont edit the code.
- you can freeliy edit the settings of the hold action like duration, icons etc.
- dont edit the code of the holdactions steps.