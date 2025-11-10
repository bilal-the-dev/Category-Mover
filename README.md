## What is Modmail?

With this fork, add in `.env`

```bash
CATEGORY_AWAITING_USER_ID=1417102117658820608
CATEGORY_AWAITING_STAFF_ID=1417102120188117078
```

CATEGORY_AWAITING_USER_ID = Category ID where bot will move when staff replies to thread (?reply)
CATEGORY_AWAITING_STAFF_ID = Category ID where bot will move when user replies in DM

Modmail is similar to Reddit's Modmail, both in functionality and purpose. It serves as a shared inbox for server staff to communicate with their users in a seamless way.

This bot is free for everyone and always will be. If you like this project and would like to show your appreciation, you can support us on **[Patreon](https://www.patreon.com/kyber)**, cool benefits included!

For up-to-date setup instructions, please visit our [**documentation**](https://docs.modmail.dev/installation) page.

## How does it work?

When a member sends a direct message to the bot, Modmail will create a channel or "thread" into a designated category. All further DM messages will automatically relay to that channel; any available staff can respond within the channel.

Our Logviewer will save the threads so you can view previous threads through their corresponding log link. ~~Here is an [**example**](https://logs.modmail.dev/example)~~ (demo not available at the moment).

## Features

- **Highly Customisable:**

  - Bot activity, prefix, category, log channel, etc.
  - Command permission system.
  - Interface elements (color, responses, reactions, etc.).
  - Snippets and _command aliases_.
  - Minimum duration for accounts to be created before allowed to contact Modmail (`account_age`).
  - Minimum length for members to be in the guild before allowed to contact Modmail (`guild_age`).

- **Advanced Logging Functionality:**

  - When you close a thread, Modmail will generate a log link and post it to your log channel.
  - Native Discord dark-mode feel.
  - Markdown/formatting support.
  - Login via Discord to protect your logs ([premium Patreon feature](https://patreon.com/kyber)).
  - See past logs of a user with `?logs`.
  - Searchable by text queries using `?logs search`.

- **Robust implementation:**
  - Schedule tasks in human time, e.g. `?close in 2 hours silently`.
  - Editing and deleting messages are synced.
  - Support for the diverse range of message contents (multiple images, files).
  - Paginated commands interfaces via reactions.

This list is ever-growing thanks to active development and our exceptional contributors. See a full list of documented commands by using the `?help` command.

## Installation

There are a number of options for hosting your very own dedicated Modmail bot.

Visit our [**documentation**](https://docs.modmail.dev/installation) page for detailed guidance on how to deploy your Modmail bot.

### Patreon Hosting

If you don't want the trouble of renting and configuring your server to host Modmail, we got a solution for you! We offer hosting and maintenance of your own, private Modmail bot (including a Logviewer) through [**Patreon**](https://patreon.com/kyber).

## FAQ

**Q: Where can I find the Modmail bot invite link?**

**A:** Unfortunately, due to how this bot functions, it cannot be invited. The lack of an invite link is to ensure an individuality to your server and grant you full control over your bot and data. Nonetheless, you can quickly obtain a free copy of Modmail for your server by following our [**documentation**](https://docs.modmail.dev/installation) steps or subscribe to [**Patreon**](https://patreon.com/kyber).

**Q: Where can I find out more info about Modmail?**

**A:** You can find more info about Modmail on our [**documentation**](https://docs.modmail.dev) page. If you run into any problems, join our [Modmail Discord Server](https://discord.gg/cnUpwrnpYb) for help and support.

## Plugins

Modmail supports the use of third-party plugins to extend or add functionalities to the bot.
Plugins allow niche features as well as anything else outside of the scope of the core functionality of Modmail.

You can find a list of third-party plugins using the `?plugins registry` command or visit the [Unofficial List of Plugins](https://github.com/modmail-dev/modmail/wiki/Unofficial-List-of-Plugins) for a list of plugins contributed by the community.

To develop your own, check out the [plugins documentation](https://github.com/modmail-dev/modmail/wiki/Plugins).

Plugins requests and support are available in our [Modmail Support Server](https://discord.gg/cnUpwrnpYb).

## Sponsors

Special thanks to our sponsors for supporting the project.

SirReddit:
<br>
<a href='https://www.youtube.com/channel/UCgSmBJD9imASmJRleycTCwQ/featured'>
<img height=100 src='https://i.imgur.com/WyzaPKY.png' style='margin:5px'>
</a>
<br>
<br>
Prime Servers Inc:
<br>
<a href='https://primeserversinc.com/'>
<img height=100 src='https://i.imgur.com/sVcwtt8.png' style='margin:5px'>
</a>
<br>
<br>
Real Madrid:
<br>
<a href='https://discord.gg/realmadrid'>
<img height=100 src='https://i.imgur.com/9Rat2Qb.png' style='margin:5px'>
</a>
<br>
<br>
Advertise Your Server:
<br>
<a href='https://discord.gg/zP8KcF4VQz'>
<img height=100 src='https://user-images.githubusercontent.com/45324516/140673115-dd3e873c-36b6-4383-9eb4-db42e1986ab3.png' style='margin:5px'>
</a>
<br>
<br>
Help Us • Help Other's:
<br>
<a href='https://discord.gg/5yQCFzY6HU'>
<img height=100 src='https://i.imgur.com/Gi3jxeH.gif' style='margin:5px'>
</a>
<br>
<br>
Discord Advice Center:
<br>
<a href='https://discord.gg/zmwZy5fd9v'>
<img height=100 src='https://i.imgur.com/1hrjcHd.png' style='margin:5px'>
</a>
<br>
<br>
Blacklight Promotions:
<br>
<a href='https://blacklightpromotions.online'>
<img height=100 src='https://i.imgur.com/yLgE6h6.png' style='margin:5px'>
</a>

Become a sponsor on [Patreon](https://patreon.com/kyber).

## Contributing

Contributions to Modmail are always welcome, whether it be improvements to the documentation or new functionality, please feel free to make the change. Check out our [contributing guidelines](https://github.com/modmail-dev/modmail/blob/master/.github/CONTRIBUTING.md) before you get started.

If you like this project and would like to show your appreciation, support us on **[Patreon](https://www.patreon.com/kyber)**!

## Beta Testing

Our [development](https://github.com/modmail-dev/modmail/tree/development) branch is where most of our features are tested before public release. Be warned that there could be bugs in various commands so keep it away from any large servers you manage.

If you wish to test the new features and play around with them, feel free to join our [Public Test Server](https://discord.gg/v5hTjKC). Bugs can be raised within that server or in our Github issues (state that you are using the development branch though).
