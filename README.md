# rust-discord-bot

Discord bot written in rust

## Setup

Create a `.env` file in the project root:

```
DISCORD_TOKEN={from Discord gamerboys-bot app}
```

## Running

```
RUST_LOG=info cargo run
```

compiles and starts the server.

To actually enable the bot:

1. Invite it to the server following [these instructions](https://discordpy.readthedocs.io/en/stable/discord.html).
2. Start the server.
3. Commands are currently prefixed with `~`, bot will respond with chat messages. Try `~ping` and `~multiply`.
4. `~quit` actually shuts down the server so we'll probably need to remove that.
