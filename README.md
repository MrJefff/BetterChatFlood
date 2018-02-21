This plugin prevents chat flooding for both normal chat and BetterChat. It also has a configurable flood cooldown (5 seconds by default).

**Only supported with BetterChat 5.0.6 or greater!**
**Also may not work with other chat interception plugins.**

## Dependencies
### Optional
- [Better Chat](https://umod.org/plugins/betterchat)

## Permissions
- `betterchatflood.bypass` -- Players with this permission will bypass the flood cooldown.

## Configuration 
```json
{
  "Permission Name": "betterchatflood.bypass",
  "Cooldown Period (seconds)": 5.0,
  "Number of messages before cooldown": 3
}
```
**Permission Name:** Permission to be used to bypass the message cooldown.

**Cooldown Period (seconds):** Amount of seconds the player cannot chat for once they have a cooldown.

**Number of messages before cooldown:** Number of messages a player sends within the cooldown amount before they're blocked from chatting.

## Localization
```json
{
  "Cooldown": "Try again in {0} seconds"
}
```
