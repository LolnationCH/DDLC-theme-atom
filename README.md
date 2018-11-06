# Doki Doki Literature Club atom theme

Atom theme made based on the game Doki Doki Literature Club (DDLC). All assets (images) come from the game itself.

To change the club member, you have to go to `styles/colors.less`, and change the value of `@current_member` to one of the value in `@club_members`.

Have a different scheme for all the members :
## Monika
![Monika Theme](https://i.imgur.com/6PegmHi.png)

## Natsuki
![Natsuki Theme](https://i.imgur.com/OspyLdo.png)

## Sayori
![Sayori Theme](https://i.imgur.com/d2ORm9d.png)

## Yuri
![Yuri Theme](https://i.imgur.com/RsaAlOv.png)

## Changing colors
The club members have each their own color scheme, that can be change in the `styles/club_members`. I recommend using a color-picker package and pigment. These will save you some time.
For live reloading (sometimes you still needs to press `ctrl-shift-F5`, don't know why), open Atom in dev mode, from the view menu.
Also, the guide for creating theme from scratch is [Here](https://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/).

## Changing the background
I recommend using a website like [imgur](https://imgur.com/) to host your background. You need to specify a url in the club member style, variable `@theme-main-background-image`.
> If you are using imgur as the host site, `@theme-main-background-image` can be set like this : `"@{image_directory}{id}.png";` where {id} comes from `https://i.imgur.com/{id}.png`.
`@{image_directory}` is already set to be equal to `https://i.imgur.com/`.
