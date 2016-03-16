# normify.css v0.1

Forked from [Normalize.css](https://github.com/necolas/normalize.css) - "customisable CSS file that makes browsers render all
elements more consistently and in line with modern standards."

More:

- opinionated
- responsive
- still no classes

A note on flexible elements: automatic fluidity (max-width: 100%) is applied to img. [Fluidity](http://fluidity.sexy/) applies it to canvas, iframe, video, and svg as well, but normify.css doesn't.

The reason for this choice is: images are very frequently used. They may be dropped all over the place without any specific styling applied. They are often content, like text. Text flows automatically. So let images squish automatically.

But the use of canvas and the rest of them is likely to be more deliberate, and carefully considered styling will be applied to them as a matter of course. And you might decide in those cases that the width should be allowed to exceed its container. Or not. Cross that bridge when you come to it.

Classes are good. You should add lots of them to your markup.
