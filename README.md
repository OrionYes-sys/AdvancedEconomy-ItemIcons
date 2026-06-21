# AdvancedEconomy Item Icons

Unturned item icons exported from `Extras/Icons`, renamed to `{id}.png` for [AdvancedEconomy](https://restoremonarchy.com/) Store UI.

## URL pattern

```
https://raw.githubusercontent.com/OrionYes-sys/AdvancedEconomy-ItemIcons/main/{id}.png
```

Example: `https://raw.githubusercontent.com/OrionYes-sys/AdvancedEconomy-ItemIcons/main/36449.png`

## AdvancedEconomy config

In `Plugins/AdvancedEconomy/AdvancedEconomy.configuration.xml`:

```xml
<ItemIconBaseUrl>https://raw.githubusercontent.com/OrionYes-sys/AdvancedEconomy-ItemIcons/main</ItemIconBaseUrl>
<ItemIconUseGuid>false</ItemIconUseGuid>
<EnableStoreUI>true</EnableStoreUI>
```

Reload the plugin or restart the server after saving.
