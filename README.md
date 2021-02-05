# DiscordGo
Discord C2 for Redteam....Need a better name.
If you can think of one, please tell me. :)


# Why I made this

During Blue-Red Team competition, I needed an easy and fast way to keep connected.
Since Discord is getting popular, why not use the platorm as a c2.
That's what this project is about.

# How to use

* Compile the binary
* Run in on your target
* Now wait, and you should get a notification about a new channel being created

* Video coming soon

![alt text](./img/command.png "Command example")
![alt text](./img/teams.png "Team list")


# Build

`go build main.go`

# TODO

~~- [x] Statically comile the config file (I used environment variable)~~

- [ ] Cross-platorm
- [ ] File upload and download

# Config file

~~This is example config. Replace the bot_token and server_id with yours and you should be good to go~~

For easy compilation, I changed the code so that the token and is are compiled directly into the binary.
So change the `botToken` and `id` variable in top of the main.go file


# Disclamers
The author is in no way responsible for any illegal use of this software. It is provided purely as an educational proof of concept. I am also not responsible for any damages or mishaps that may happen in the course of using this software. Use at your own risk.

# Used Libraries
* [disgord](https://github.com/andersfylling/disgord)


Inspired by [SierrOne](https://github.com/berkgoksel/SierraOne)