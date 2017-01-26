# Complex Web Page From Mockup

I set a puzzle for myself. Find a really complicated web page mocked up
in photoshop and code it up in HTML. I wanted something ugly and messy
that required lots of pixel-fiddling. And boy did I get what I asked for.

This web page mockup comes from GraphicsFuel.com. It presents some
really interesting challenges and demonstrates many of the techniques
from the glory days of over-produced web pages.

First, I had to extract all the image components from the photoshop PSD file.
Only the image components in the PSD differed in places from the associated
JPG image. So I had to play with the image components. In one case I had to
reassemble the large coffee cup / lemon image from a bunch of circles and
the almost transparent steam wisp. I had to reassemble the main logo and didn't
do a great job with the outrider curls.

Next, the colors. The mockup uses a number of colors I had to extract using
a color-dropper against a JPG file. So my palette has some variations another
pass over the code would reduce.

The composite background is tricky. It had a chocolate brown woodgrain top section
followed by a light brown plaster image that fades off to a medium brown background
color that fills the rest of the page. The mockup also has a vertical shadow that
I decided not to add.

The "search" text in the search box. I got tired manipulating the alignment of
this text. One more pass and a larger "top" value might have fixed it. But I
wanted to move on.

The dotted lines. What a bit of CSS juggling to get the various page segements
to meet so their border boxes lined up.

The social media icons with their associated curls were laid right on top of
a border box dotted line. The solution is easy (position: relative;) but
masking the underlying dotted box took a slight bit of trickery.

This web page has a bit over 80 CSS rules and 200 lines of html. There are a lot
of DIV elements needed to make the web page model the mockup.

It was a fun puzzle.
