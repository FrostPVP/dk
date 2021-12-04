on join:
  set join message to: "&7%Player%&8[&a+&8]"

on quit:
  set join message to: "&7%Player%&8[&c+&8]"

on first join:
  set join message to: "&7Welcome to &8Box&bServer&855&7, %player%"
  
command /hi
  command cooldown: "10"
  command cooldown message: "&l&4Wait"
    send: "hello %Player%"
