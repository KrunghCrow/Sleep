**Sleep** allows players with permission to get a well-rested sleep. While sleeping, players may grow hungry, get thirsty, and even get a bit dirty depending on settings.

By default, players will heal and restore 5 percent of their current levels every 10 seconds; and get dirty, hungry, and thirsty by 5 percent of their current levels every 10 seconds. Curing is also available, but disabled by default. Everything is changeable in the configuration file.

## Permissions

- `sleep.allow` -- Allows players to go to sleep

## Commands

This plugin provides universal chat and console commands. When using a command in the chat, prefix it with a forward slash `/` or the symbol you have configured in `umod.config.json`.

- `sleep` -- Make yourself go to sleep and rest

## Configuration

```json
{
  "Cure while sleeping (true/false)": false,
  "Heal while sleeping (true/false)": true,
  "Restore while sleeping (true/false)": true,
  "Curing rate (0 - 100)": 5,
  "Healing rate (0 - 100)": 5,
  "Restoration rate (0 - 100)": 5
}
```

## Localization

```json
{
  "Command": "sleep",
  "Dirty": "You seem to be a bit dirty, go take a dip!",
  "Hungry": "You seem to be a bit hungry, eat something",
  "NotAllowed": "You can't go to sleep right now",
  "Restored": "You have awaken restored and rested!",
  "Thirsty": "You seem to be a bit thirsty, drink something!",
  "WentToSleep": "You went to sleep."
}
```
## Credits

- **Wulf**, the original author of this plugin
