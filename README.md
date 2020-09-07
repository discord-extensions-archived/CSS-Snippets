# CSS Snippets for Powercord / BetterDiscord
These are some random CSS snippets I decided to throw together for either importing into themes or just using as is. If you wanna use these for themes, feel free to. Also note that these probably aren't coded the best way that they could be coded, they're only intended to work as is. These should work on both Powercord and BetterDiscord
### If you'd like to import all of these snippets, go to your Themes folder, open a command prompt / powershell / terminal / or git bash and run:

	git clone https://github.com/LuckFire/CSS-Snippets


## More Rounded Borders
Make borders that are some-what rounded more rounded.
### Preview
![Preview ](https://cdn.discordapp.com/attachments/738968109288914976/751152635196735528/unknown.png)
### Installtion
If you'd like to import this snippet, go to your **Themes tab, open Quick CSS** and paste the following: 

	@import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/MoreRoundedBorders/borders.css")
  

## White Chatbar
If you're using dark theme but want a white chatbar, this will do that.

### Preview
![Preview](https://cdn.discordapp.com/attachments/738968109288914976/752401843036094494/unknown.png)  
![Preview](https://cdn.discordapp.com/attachments/738968109288914976/752322486938632263/unknown.png)

### Installtion
If you'd like to import this snippet, go to your **Themes tab, open Quick CSS** and paste the following:

    @import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/WhiteChatbar/textbar.css")

## Custom Highlight Colors
Customize the ping as well as Clyde's highlight colors.

### Preview 
![Cool Colors!!](https://cdn.discordapp.com/attachments/738968109288914976/752296542207213653/unknown.png)

### Installtion
If you'd like to import this snippet, go to your **Themes tab, open Quick CSS** and paste the following:

    @import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/CustomHighlightColor/highlight.css");

    :root {
            --background-mentioned-side: rgb(114, 137, 218);
            --background-mentioned: rgba(114, 137, 218, 0.05);
            --background-mentioned-hover: rgba(114, 137, 218, 0.12);
            --local-bot-side: rgb(240, 71, 71); 
            --local-bot-default: rgba(240, 71, 71, 0.05);
            --local-bot-hover: rgba(240, 71, 71, 0.12);
    }



## Custom Link Colors
Add some spice to the coloring of links.

### Preview
![Preview](https://cdn.discordapp.com/attachments/738968109288914976/752318169531809802/unknown.png)

### Installation
If you'd like to import this snippet, go to your  **Themes tab, open Quick CSS**  and paste the following:

	@import url("https://raw.githubusercontent.com/LuckFire/CSS-Snippets/master/CustomLinkColors/linkcolors.css")
	:root {
   		--text-link: rgb(135, 206, 235) !important;
   		--text-link-hover: rgb(30, 144, 255);
   		--text-link-author: rgb(255, 255, 255);
	}

## Better Channel Indicators
Inspired by hellbound's Modern Indicators, I've remade this but made them a bit better.

### Preview
![Preview](https://cdn.discordapp.com/attachments/738968109288914976/752394554812137502/unknown.png)

### Installtion
If you'd like to import this snippet, go to your **Themes tab, open Quick CSS** and paste the following:

    @import url("https://raw.githack.com/LuckFire/CSS-Snippets/master/BetterChannelIndicators/indicators.css");

    :root {
            --unread-badge: rgba(255,255,255,0.6) !important;
            --unread-bg: rgba(255, 255, 255, 0.01) !important;
            --selected-badge: rgb(112, 135, 215) !important;
            --selected-bg: rgba(112, 135, 215, 0.1) !important;
            --hovered-bg: rgba(79,84,92,0.25) !important;
            --bg-rounding: 0px 10px 10px 0px !important
    }
