1102 X 647

### OLEX NOTES

## Eric Snell
> https://ericsnell.github.io/portfolio/

### Content
Overall, very good copy. "Hi I'm eric" is a bit trite, but it could be
fine, just use a more distinctive font or make "Hi," bigger or something.

"Hi I'm Eric" in about me just repeats the above.
About me & footer - good on copy. You can add soundcloud to social
links.

Missing: Projects

### Type, Colors, Look & Feel
Font sizes (font-size and line-height) seem quite good. Montserrat
:thumbs-up:. The text shadow is just making your text look blurry, I
tend to use shadows to seperate _similar_ colors, not black + white.
Speaking of black, you have a nice dark-gray, you should use that for
fonts as well e.g. `body { color: #333; }`.

Nav feels small, You can make it big and opaque and it's still be fine,
I'd play with that.

I think the github + demo buttons are a little YUGE. You should add the
text like "Demo" and "Source & Info" or something like that. Add titles.
For description / tech used you can use your `readme.md` files in github
and keep your portfolio clean. But I still think you need titles here.

### Responsive
Mobile sizes: very kafkaesque, huge icons for github / eye in the
projects section. About etc font sizing is too large. protip: line-height of
`1.5+` works on wide paragraphs, but with fewer chars per line,
`line-height` should also be a bit smaller.

Yeah just poke around it on your phone and change it up.

Interesting that you have NO default styles, they're all in (width >=
320px)... You should just put those outside of a media query. Not a big
deal tho.

White border around body seems a bit pointless, did you use `normalize`
or `reset`? Either of those would remove it or it
(or just `body { margin: 0; }`)

### Take-away
Work on your projects section, those assets take some effort.

Your site is a good example of how simple works best. Will be showing it
to some other students (whose sites are overthinking it :D)

Looking forward to a version w/ projects and a few more
responsive tweaks. Incomplete, but great job so far!




### JOE TURNER NOTES

# Design

* All caps titles look like shouting.
* Kill the drop shadows - they should be used (very) sparingly as more of a stand-out effect.
* Font size on the title bar links is a bit small.
* Your top image should be actually full-width.
* The sticky nav is probably overkill for a page of this length - just have it as a static top bar.
* The rounded corners on your profile picture clash a bit with the sharp edges everywhere else.
* The project links moving below the images when your site has limited width is a bit strange.
* Projects on the front-page would be more effective as full-width divs rather than tiles.
* Add some text (Code/Demo) next to the project links so it's obvious what they do.

# Content

* Needs the actual projects :)
* Generally Facebook links are left out of portfolios - it looks a bit more personal than professional.
* Add text with the Email/GH/LinkedIn logos, in case they aren't recognised.


# Nits

* coffe -> coffee
