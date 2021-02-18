# kbpv6000-resources
guide and info on the kbparadise keyboard since i found it hard to find info when i got mine.

(resources for the kbp v6000 kb Paradise v60 type R made in Taiwan)

## models

- [V60](https://www.kbparadise.com/discontinue-v60) firmware not allow key map ( programmable ) , only adjust couple keys by 6 port dip switch at back side. (original, discontinued)
- [V60 Type R](https://www.kbparadise.com/v60type-r) , use open source firmware , end user can programmable via QMK / TMK / TKG tool. (no DIP switch, so fits more cases but supports & needs programming if changing keys) 
- [V60 Type R Polestar](https://www.kbparadise.com/v60type-r) same as type R but with RGB underglow.
- [V60the2](https://www.kbparadise.com/v60the2) unreleased (feb 2021)

### jargon for casual keyboard-people
When people say v60 they might mean any of the v60 versions with any of the switches.
There is a difference between models so try figure out what they are talking about.
example:
- v60 has dip switches on back
- v60 type R has a reset button instead

when anyone says v60 Mattias, the mattias refers to the switches. same with v60 cherry brown, or v60 khali blue

# modify key mapping

## TKG program guide for the v60 (2017) 
(at the time of writing this, the keyboard is not fully supported by qmk.)

- [original blogpost](http://www.bytesizedworkbench.com/blog/programming-the-kbparadise-v60-polestar-keyboard/) 
- backup pdf in this repo
- [backup on someones dropbox](https://www.dropbox.com/s/fov3y87rvondxy9/programming%20the%20KBParadise%20V60%20polestar%20keyboard%20_%20ByteSizedWorkbench.pdf?dl=0)


## VIA
- [via repo](https://github.com/the-via/keyboards) 
- [git releases](https://github.com/the-via/releases/releases/tag/v1.3.1)
- official website: https://caniusevia.com/

not much info on the repo or the website so here is a description

**description:**
 it is an application that allows you to change the keys, lighting options and configure your QMK Keyboard instantly, without the necessity of flashing a hex file. With V1, we’ve added a bunch of new features including but not limited to, a keyboard/matrix tester, macro support, custom keycodes, configurable layouts and a mode for keyboard designers to test their integration.
 
 Via is built on QMK. If your keyboard is on the caniusevia.com list, you’ll still need to have a VIA-compatible firmware loaded. It may or may not have one already, but you can download and flash it if it doesn’t. You can tell by just launching the Via software with the keyboard plugged in. it will detect your keyboard if it does. (plug directly in your pc instead of a USB hub)
 
 see this reddit post for a img preview https://www.reddit.com/r/MechanicalKeyboards/comments/kzffd3/help_with_via/
 
 tried it but doesn't work with current windows release (17/02/2021)
 they have added kb paradise files in their repo though

from what i understand VIA is build on top of QMK 

## QMK

QMK repo https://github.com/edwinclement08/qmk-firmware/tree/237dd23491cff3dc60df123a8992301bd1d8a9c8
(13 days ago VIA support was added to QMK)

## modify fn key virtually

### spacefn
virtually remap fn key to spacebar. hold spacebar + key will use spacebar as fn key. pressing spacebar will act as normal space bar. Bonus. It works with any keyboard 😊
- [original post on spacefn concept 2015](https://geekhack.org/index.php?topic=51069.350) 
- use TouchCursor on windows, download [here](http://touchcursor.sourceforge.net/)
- or here: [TouchCursor releases on github](https://github.com/martin-stone/touchcursor/releases)

# official website
old website available on wayback machine: www.kbp.com.tw
https://web.archive.org/web/20190919164709/http://www.kbp.com.tw/product.html

new website: www.kbparadise.com
https://www.kbparadise.com/v60type-r
**Todo create backup of this page in this repo**

# manuals

## 2 page manual on key shortcuts 
- [online pdf](https://kupdf.net/download/kbp-v60-user-manual-_59c1659c08bbc5f82368700e_pdf) 
- backup on repo

note: it mentions fn-return unlocks arrow keymode, marked by led at return.
this doesnt work on my non led v60 type R
backlight shortkeys obviously also don't work

### case compatibility
- a [reddit posts](https://www.reddit.com/r/MechanicalKeyboards/comments/6h0tom/anne_pro_vs_kbparadise_v60/diul7fk?utm_source=share&utm_medium=web2x&context=3) mentions it's  easy to swap out the case of the v60 (but doesn't specify which v60). 
- A [youtube review](https://www.youtube.com/watch?v=8GbpDFgE6Mo) on the original V60 mentions that isn't the case because of the massive DIP switch on the back, making it incompatible with most cases. 
- the V60 type R doesn't has the DIP switch so might fit other cases better.

### keycap compatibility
should fit any standard 60% layout keys, any cherry caps types
so compatible with most PBT keys out there.
TODO add source

# related git repos
found these on github, not sure if they are usefull
- (QMK) [A keymap for KBParadise v60 Type R (60 ANSI layout)](https://github.com/aorfanos/effective_v60typer)
- (QMK) [Custom layout for a Keyboard Paradise V60](https://github.com/paul-krohn/qmk-keyboard-layout) 
- [scripts for mac keyboards](https://github.com/richdawe/mac-keyboards) 


# youtube reviews
https://www.youtube.com/watch?v=8GbpDFgE6Mo
https://www.youtube.com/results?search_query=kbparadise+v60

# reddit posts
### KBParadise v60
- [Anne Pro vs KBParadise v60?](https://www.reddit.com/r/MechanicalKeyboards/comments/6h0tom/anne_pro_vs_kbparadise_v60/) 
- [Is the KB paradise v60 any good?](https://www.reddit.com/r/MechanicalKeyboards/comments/3uzdd6/helpis_the_kb_paradise_v60_any_good/) 
- [Convince me of the benefits of a pok3r over a kbparadise v60](https://www.reddit.com/r/MechanicalKeyboards/comments/4ansst/convince_me_of_the_benefits_of_a_pok3r_over_a/) 
- [KBP v6000 with Matias Quiet click new Work keyboard](https://www.reddit.com/r/MechanicalKeyboards/comments/4egqaz/photoskbp_v6000_with_matias_quiet_click_new_work/) 

### generic mechanical keyboard
- [reddit generic mechanical keyboard buying guide](https://www.reddit.com/r/MechanicalKeyboards/wiki/buying_guide) 
- [reddit generic mechanical keyboard wikki](https://www.reddit.com/r/MechanicalKeyboards/wiki/index) 

# reviews
[blogpost polestar review](https://www.keyboardco.com/blog/index.php/2017/06/kbparadise-v60-type-r-polestar-edition-review/) 


# specs for the standard black v60 without leds
Default Keycaps: Primary: Black Pad Printed ABS with White legends
Details and Specifications
Brand	KBParadise
Model	V60
Size	60%
Switch Stems	ALPS, MX
Physical Layout	ANSI
Logical Layout	US QWERTY (i got mine in UK QWERTY)
Frame Color	Black
Primary LED Color	n/a
Control LED Color	n/a
USB Key Rollover	6
Multimedia Keys	Yes
Switch Mount Type	Plate
Built in Audio Port	No
Built in Mic Port	No
Interface(s)	USB
Windows Compatible	Yes
Mac Compatible	Yes
Linux Compatible	Yes
Dimensions	3.94" x 11.46" x 1.67"
Weight	1.12 lbs
Cord Length	60 inches

MCU controller ATMega32u4
QMK - Fully Programmable open source (Not support PS4)
standard ansi layout
Cherry MX switch

# other 
would be cool if i can find some softwware that can visualise your current layers
similar to this but triggered as an overlay on your pc using a shortkey http://waldobronchart.github.io/ShortcutMapper/#AdobePhotoshop
update: via seems to kind of do this? not working yet though


