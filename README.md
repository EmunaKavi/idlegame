# idlegame

[![PyPI](https://github.com/bboonstra/idlegame/actions/workflows/pypi.yml/badge.svg)](https://github.com/bboonstra/idlegame/actions/workflows/pypi.yml)
[![Unit Tests](https://github.com/bboonstra/idlegame/actions/workflows/tests.yml/badge.svg)](https://github.com/bboonstra/idlegame/actions/workflows/tests.yml)

Ever find yourself stuck at your desk during slow moments in software development? **idlegame** is here to save the day! Whether you’re waiting for a build to finish or just need a quick breather, this idle game is your perfect companion to make those downtime moments a little more fun.

## Installation

Getting started with **idlegame** is a breeze. Just whip out your terminal and run:

```bash
pip install idlegame
```

## Usage

Once it’s installed, you can jump right in by typing:

```bash
idlegame
```

## Features

- **Easy to Play**: I literally can't think of a way to make it easier. Install and run in 2 steps!
- **Casual Gameplay**: Ideal for short breaks or when you need to step away from coding.
- **Offline Play**: Even when you’re not actively playing, your nanobots are hard at work.
- **IncrediSave**: Automatic saves mean you’ll never lose progress. It’s like magic.

## How To Play

**idlegame** is a game made for two purposes. One, to entertain you at work. Two, to teach you some zsh commands.
To that end, every command in idlegame is a valid zsh command (or helper command, or real cli).
Play the game by scripting nanobots with nano. These nanobots can collect resources, defend your filetree, and more.

For example,

### Quickstart

```zsh
Logged in as: bb
bb@idlegame % uptime
Here, you'll be able to see what has happened since you last checked on the uptime of your nanobots.
You can create a nanobot with `nano`, but it requires a nanocore. Here's one to get you started.
Recieved: 1 basic nano core
bb@idlegame % nano --name mine&defend -y
Write the logic for your nanobot (type 'done' on a new line to finish):
idle mine
on invasion defend
done
Nanobot 'mine&defend' created!
bb@idlegame % ls
Name           Type      Idle Action    Event Actions                 Current Action                
----------------------------------------------------------------------------------------------------
mine&defend    Normal    Mine           On invasion: defend           Performing idle action: mine  
----------------------------------------------------------------------------------------------------
bb@idlegame % 
```

The zsh above shows an efficient way to get started. Claim a nano core, and use it to create a Nanobot that mines for gold. However, if someone invades you, the Nanobot will help defend. This is a very useful all-purpose bot.

## I'm stuck

```zsh
man
```

`man` will tell you anything you need to know! It will list all the commands available to you, or use `man [command name]` to get specifics.

## Player's Guide
-- **Experiment with Commands**: Don’t hesitate to try out different zsh commands to see how they interact with your nanobots. The more you explore, the more effective your bots will become!

-- **Strategize Your Nanobots**: Think carefully about how you want your nanobots to behave. Create specialized bots for different tasks, such as mining, defending, or resource gathering. A balanced team will yield better results.

-- **Stay Updated**: Keep an eye on the commands and features available. New updates may introduce new commands or improve existing ones, enhancing your gameplay experience.

-- **Utilize man Wisely**: The man command is your best friend! Use it to familiarize yourself with available commands and their functionalities.

-- **Join the Community**: Engage with other players or contribute to the development of idlegame. Sharing tips, tricks, and feedback can lead to a more enjoyable experience for everyone.

## Contributing

Got ideas or feedback? We’d love to hear from you! Feel free to submit a pull request or open an issue on the GitHub repo. Your thoughts can make **idlegame** even better :>
### Check out [CONTRIBUTING](CONTRIBUTING.md) to get started!

Enjoying idlegame? Give us a star on GitHub!

## License

This project is licensed under the MIT License. Check out the [LICENSE](LICENSE) file for more details.
