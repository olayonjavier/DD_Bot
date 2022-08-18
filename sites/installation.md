# **How to Install DD_Bot**

1. Get a [Discord Bot](/sites/discordbot.md)
2. Install [Docker](https://www.docker.com/get-started/)
3. Pull DD_Bot Image using `docker pull assaro/ddbot`
4. Start image using `docker run -d --name='DD_Bot'  -v 'path/to/settings':'/app/settings/':'rw' 'assaro/ddbot:latest' `
    - For Unraid, please refer to [this Screenshot](/pics/Unraidsettings.png)
5. The Container will generate a settings file in your set directory
6. Stop the Container, input your settings and then start it again. [Click for info about settings](/sites/settings.md)
    - Everything but the Discord Token can be changed while the container is running
7. You should be good to go, if not, see  [discordbot](/sites/discordbot.md), [settings](/sites/settings.md) or [faq](/sites/faq.md)
8. If something is still not working, feel free to dm me or open an issue