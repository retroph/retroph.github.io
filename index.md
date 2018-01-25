# Projects
## Speedrun Stuff

My current small project playing with the public [Speedrun.com](https://www.speedrun.com/) [API](https://github.com/speedruncomorg/api) and Discord/Twitter: [speedrun-watch](https://github.com/retroph/speedrun-watch)

[Bugs / Issue tracker](https://github.com/retroph/speedrun-watch/issues) - don't hesitate to report problems you see in posted runs, either there or directly on Twitter.

### Twitter Bots

I run several Twitter accounts posting new verified runs for several retro platforms.
More coming soon.

Note: some runs for alternative platforms like VC are still missing, will be added soon.

{% for account in site.data.twitter %}
- [{{ account.desc }}](https://twitter.com/{{ account.name }})
{% endfor %}

### Discord Bots

- Sega Master System new submitted runs on the [MasterSystem.racing](http://mastersystem.racing/) Discord server
- Mega Drive / Genesis / Sega CD / 32X new submitted runs on the [Mega 16 Discord server](https://discord.gg/5TRErds)
- Many retro platforms on my [personal Discord server](https://discord.gg/nrB5Fss)

Just message me if you want a runs feed added to your discord channel!

## Twitter List

[View list on Twitter](https://twitter.com/_RPH_/lists/platform-speedruns-bots)

{% include twitter-bots.html %}

