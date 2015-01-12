# botyonce

botyonce is a chat bot built on the [Hubot][hubot] framework. It was initially generated by [generator-hubot][generator-hubot], configured to be deployed on [Heroku][heroku] to get you up and running as quick as possible, and imbued with a subconscious desire for complete world domination.

This README is intended to help get you some tacos.

[heroku]: http://www.heroku.com
[hubot]: http://hubot.github.com
[generator-hubot]: https://github.com/github/generator-hubot

### Running botyonce Locally

You can test your hubot by running the following.

You can start botyonce locally by running:

    % bin/hubot

You'll see some start up output about where your scripts come from and a
prompt:

    [Sun, 04 Dec 2011 18:41:11 GMT] INFO Loading adapter shell
    [Sun, 04 Dec 2011 18:41:11 GMT] INFO Loading scripts from /home/tomb/Development/hubot/scripts
    [Sun, 04 Dec 2011 18:41:11 GMT] INFO Loading scripts from /home/tomb/Development/hubot/src/scripts
    Hubot>

Then you can interact with botyonce by typing `botyonce help`.

    botyonce> botyonce help

    botyonce> animate me <query> - The same thing as `image me`, except adds a few
    convert me <expression> to <units> - Convert expression to given units.
    help - Displays all of the help commands that Hubot knows about.
    ...


### Scripting

An example script is included at `scripts/example.coffee`, so check it out to
get started, along with the [Scripting Guide](https://github.com/github/hubot/blob/master/docs/scripting.md).

For many common tasks, there's a good chance someone has already one to do just
the thing.

### hubot-scripts

There will inevitably be functionality that everyone will want. Instead
of writing it yourself, you can check
[hubot-scripts][hubot-scripts] for existing scripts.

To enable scripts from the hubot-scripts package, add the script name with
extension as a double quoted string to the `hubot-scripts.json` file in this
repo.

[hubot-scripts]: https://github.com/hubot-scripts

### external-scripts

Hubot is able to load scripts from third-party `npm` package. Check the package's documentation, but in general it is:

1. Add the packages as dependencies into your `package.json`
2. `npm install` to make sure those packages are installed
3. Add the package name to `external-scripts.json` as a double quoted string

You can review `external-scripts.json` to see what is included by default.

## Contributing

1. Fourq it
2. ???
3. #hashtag

## Commands

 <spotify link> - returns info about the link (track, artist, etc.)

 What is bikeshedding? - Display an explaination of bikeshedding

 bikeshed - Gives a suggestion of a bikeshed color

 bikeshedding - Gives a suggestion of a bikeshed color

 devops reactions

 fuck yeah <noun> - Displays a fuck yeah image for the given noun

 botyonce adapter - Reply with the adapter

 botyonce animate me <query> - The same thing as `image me`, except adds a few parameters to try to return an animated GIF instead.

 botyonce ascii me <text> - Show text in ascii art

 botyonce clojure|clj [script] - Evaluate one line of Clojure script

 botyonce don't keep http://ninjas-20.herokuapp.com alive - Remove inputted url to the collection of urls set to be pinged

 botyonce echo <text> - Reply back with <text>

 botyonce flip - botyonce flips a table

 botyonce hangout me [title] - Creates a Hangout with the given title and returns the URL.

 botyonce image me <query> - The Original. Queries Google Images for <query> and returns a random top result.

 botyonce keep http://ninjas-20.herokuapp.com alive - Add inputted url to the collection of urls set to be pinged

 botyonce map me <query> - Returns a map view of the area returned by `query`.

 botyonce mustache me <query> - Searches Google Images for the specified query and mustaches it.

 botyonce mustache me <url> - Adds a mustache to the specified URL.

 botyonce mute list - Check which channels have been muted

 botyonce mute|unmute (channel name) - (un)mute a channel (if channel name omitted, mutes current channel)

 botyonce ping - Reply with pong

 botyonce salesforce account <accountname> - searches for the account by name in Salesforce and displays all matches

 botyonce salesforce query <query> - runs an arbitrary SOQL query and outputs the results

 botyonce tell <recipients> <some message> - tell <recipients> <some message> next time they are present.

 botyonce time - Reply with current time

 botyonce translate me <phrase> - Searches for a translation for the <phrase> and then prints that bad boy out.

 botyonce translate me from <source> into <target> <phrase> - Translates <phrase> from <source> into <target>. Both <source> and <target> are optional

 botyonce twitter <command> <query> - Search Twitter for a query

 botyonce uptime <filter> - Returns uptime for sites.

 botyonce uptime add-check [http://example.com] [as [friendlyname]- Adds a new uptime check.

 botyonce weather - Get the weather for botyonce_DARK_SKY_DEFAULT_LOCATION

 botyonce weather <location> - Get the weather for <location>

 botyonce what are you keeping alive - Show list of urls being kept alive

 botyonce xkcd <num> - XKCD comic <num>

 botyonce xkcd [latest]- The latest XKCD comic

 botyonce xkcd random - XKCD comic <num>

 botyonce youtube me <query> - Searches YouTube for the query and returns the video embed link.

 botyonce: qr me <url> - turn a URL into a QR Code

 ship it - Display a motivation squirrel