# Building Twitch Overlays Using Web Technology

**👋🏻 Howdy!** We had a lunch session on January 7, 2021 where we built a custom Twitch overlay using good ol' fashioned HTML, CSS, and DOM manipulation.

We're using [ComfyJS](https://github.com/instafluff/ComfyJS) to get chat events from Twitch, and ComfyJS uses [tmi.js](https://tmijs.com/) under the hood.

We covered using browser sources in [OBS](https://obsproject.com/), which allows us to use web technologies to customize our overlays. We then introduced ComfyJS into our web page, and used its `onChat` event to trigger some DOM manipulation that would add new messages from a live feed into chatbox. We did a bit of styling based on users' moderator status, and left styling other user details like subscription status as an exercise to try on your own. Finally, we covered a bit of CSS `overflow` and flexbox to give the chatbox a more chatboxlike experience.

**Feel free to clone this repo and experiment with it yourself, or use it as a base for your own Twitch overlays. Show off what you make on our [Discord server](https://discord.gg/dx7ZWCy)!**