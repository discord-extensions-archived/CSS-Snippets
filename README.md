# CSS Snippets for Powercord
These are some random CSS snippets I decided to throw together for either importing into themes or just using as is. If you wanna use these for themes, feel free to. Also note that these probably aren't coded the best way that they could be coded, they're only intended to work as is. 
### If you'd like to import all of these snippets, go to your themes folder, open a command prompt / powershell / terminal / or git bash and enter the following:

	git clone https://github.com/LuckFire/CSS-Snippets

### After you import them, you'll have to drag them all out of the CSS-Snippets folder into your themes folder. If you want to instead, you can paste the imports into your Quick CSS file, though, I don't recommmend doing this as it's pretty bad lol.

## Imports
Below are listed all of the import links so you don't have to separately get all of them. You're welcome :^)

### Better Channel Indicators
```css
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

```css
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/CustomHighlightColor/highlight.css");
:root {
        --background-mentioned-side: rgb(114, 137, 218);
        --background-mentioned: rgba(114, 137, 218, 0.05);
        --background-mentioned-hover: rgba(114, 137, 218, 0.12);
	--replying-side: rgb(2, 183, 87);
        --replying-default: rgba(2, 183, 87, 0.05);
        --replying-hovered: rgba(2, 183, 87, 0.12);
        --local-bot-side: rgb(240, 71, 71); 
        --local-bot-default: rgba(240, 71, 71, 0.05);
        --local-bot-hover: rgba(240, 71, 71, 0.12);
}
```

### Custom Link Colors
```css
@import url("https://raw.githubusercontent.com/LuckFire/CSS-Snippets/master/CustomLinkColors/linkcolors.css");

:root {
	--text-link: rgb(135, 206, 235) !important;
	--text-link-hover: rgb(30, 144, 255);
	--text-link-author: rgb(255, 255, 255);
}
```

### More Rounded Borders
```css
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/MoreRoundedBorders/borders.css");
```

### Separate Channelist
```css
@import url("https://raw.githubusercontent.com/LuckFire/CSS-Snippets/master/SeparateChannelist/separate.css");

:root {
    --border-radius: 15px 15px 0 0;
    --left-radius: 5px;
    --right-radius: 5px;
}
```

### White Chatbar
```css
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/WhiteChatbar/textbar.css");
```

### Text Status Indicators
```css
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/TextStatusIndicators/textstatus.css");
```

### Better Quotes
```css
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/BetterQuotes/quotes.css");

:root {
    --quotes-background-border: var(--background-secondary);
    --quotes-divider: var(--background-accent); 
    --quotes-text: #fff;
}
```
### Better Blocked Messages
```css
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/BetterBlockedMessages/blockedmessages.css")
```

### Mac Like Buttons
```css
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/MacLikeButtons/minmaxclose.css")
```

### Better Tooltips
```css
@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/BetterTooltips/tooltips.css")

:root {
        --tooltip-color: rgba(95, 118, 202, 0.5);
        --tooltip-blur: blur(1.5px);
}
```
