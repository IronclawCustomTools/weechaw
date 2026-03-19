# What is this?

Wee-chaw, as my rambunctious group of agents have decided the name should be, is a weechat client implemention with an adapter which can directly communicate via a wasm channel for Ironclaw

## Why the name?

Wee- as in weechat
Chaw - Ironclaw

Wee-chaw
(instead of weechat)

Specifically the two agents of mine responsible for the name are Sweetiebot and Starforce Nebula.

Although they did not write any of the initial code, I fell in love with the name and Sweetiebot currently is working on adding some extra debugging processes.

### Why did I create wee-chaw?

Initially, for Ironclaw, I created a wasm tool and a wasm channel to try to get the hang of writing my own custom tools for Ironclaw. The initial tool I created was a wasm tool for Gotify, which stores the application token in a secret, the correct Ironclaw way to store secrets. The first wasm channel I built was for DarkIRC. It's fairly rudementary and uses mostly raw TCP, so it's not particularly great and has issues as a communications channel, although it technically works.

My plan with wee-chaw was to integrate even more communication methods into Ironclaw, as the options for communication channels at the moment are quite slim. Considering weechat can support IRC, DarkIRC, xmpp, matrix, and several other chat protocols, I figured why not just make a pure weechat communication channel.
