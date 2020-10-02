# CSS Snippets for Powercord
These are some random CSS snippets I decided to throw together for either importing into themes or just using as is. If you wanna use these for themes, feel free to. Also note that these probably aren't coded the best way that they could be coded, they're only intended to work as is. 
### If you'd like to import all of these snippets, go to your themes folder, open a command prompt / powershell / terminal / or git bash and enter the following:

	git clone https://github.com/LuckFire/CSS-Snippets

### After you import them, you'll have to drag them all out of the CSS-Snippets folder into your themes folder. I suggest that instead of doing this, you should use @import in your quickcss file or some other css file because you can keep your themes folder clean and have better management over all of them, but do as you wish.

## Imports
Below are listed all of the import links so you don't have to separately get all of them. You're welcome :^)

### Better Channel Indicators
```
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/BetterChannelIndicators/indicators.css");

:root {
        --unread-badge: rgba(255,255,255,0.6) !important;
        --unread-bg: rgba(255, 255, 255, 0.01) !important;
        --selected-badge: rgb(112, 135, 215) !important;
        --selected-bg: rgba(112, 135, 215, 0.1) !important;
        --hovered-bg: rgba(79,84,92,0.25) !important;
        --bg-rounding: 0px 10px 10px 0px !important
        --border-line-type: solid !important /* For more info on different border line types, visit https://css-tricks.com/almanac/properties/b/border/ */
}
```
### Custom Highlight Colors

```
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/CustomHighlightColor/highlight.css");
:root {
        --background-mentioned-side: rgb(114, 137, 218);
        --background-mentioned: rgba(114, 137, 218, 0.05);
        --background-mentioned-hover: rgba(114, 137, 218, 0.12);
        --local-bot-side: rgb(240, 71, 71); 
        --local-bot-default: rgba(240, 71, 71, 0.05);
        --local-bot-hover: rgba(240, 71, 71, 0.12);
}
```

### Custom Link Colors
```
@import url("https://raw.githubusercontent.com/LuckFire/CSS-Snippets/master/CustomLinkColors/linkcolors.css");

:root {
	--text-link: rgb(135, 206, 235) !important;
	--text-link-hover: rgb(30, 144, 255);
	--text-link-author: rgb(255, 255, 255);
}
```

### More Rounded Borders
```
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/MoreRoundedBorders/borders.css");
```

### Separate Channelist
```
@import url("https://raw.githubusercontent.com/LuckFire/CSS-Snippets/master/SeparateChannelist/separate.css");

:root {
    --border-radius: 15px 15px 0 0;
    --left-radius: 5px;
    --right-radius: 5px;
}
```

### White Chatbar
```
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/WhiteChatbar/textbar.css");
```

### Text Status Indicators
```
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/TextStatusIndicators/textstatus.css");
```

### Better Quotes
```
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/BetterQuotes/quotes.css");

:root {
    --quotes-background-border: var(--background-secondary);
    --quotes-divider: var(--background-accent); 
    --quotes-text: #fff;
}
```
