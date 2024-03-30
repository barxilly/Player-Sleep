# Realms Player Sleep Enabler
Sets playersSleepingPercentage to 1 whenever someone joins a realm so they don't have to faff about with commands and whatnot
## How does it work?
When the player joins the realm the following function is run:
```function
# Keep the function stfu
gamerule commandBlockOutput	false
gamerule sendCommandFeedback false
# Set the sleep percentage
gamerule playersSleepingPercentage 1
```
## Installation
Go to the [Releases Page](https://github.com/barxilly/Player-Sleep/releases), download the .mcpack file, profit.