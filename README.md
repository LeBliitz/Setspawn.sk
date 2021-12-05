command /setspawn:
    permission: use.setspawn
    trigger:
        set {spawn} to location of player
        send "&6Setspawn &7| &7Du hast den Spawn gesetzt!"

command /spawn:
    trigger:
        teleport player to {spawn}
        send "&6Setspawn &7| &7Du wurdest zum Spawn teleportiert!"
