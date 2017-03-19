# J4n-M44rt3n's BioHack Academy 4 Documentation<a id="top"></a>
Hi! My name is Jan-Maarten, but since this name was already taken on GitHub, I go by J4n-M44rt3n. I am interested in microbiological communities. No organism is an island, yet we often work with them as if they are, as evidenced by the tiny archipelagos in our petri dishes. During BHA4, I want to develop technology to study networks of living organisms. Below you will find documentation of various adventures in (more or less) this direction during BioHack Academy 4.
<BR><BR><a href="#lab">*Various labware*</a>
<BR><a href="#wgb">*Winogradsky gradient boxes*</a>
<BR><a href="#sma">*Slime mold arena*</a>
<BR><a href="#tbc">*to be continued*</a>
#
# Various labware<a id="lab"></a><BR>
**Tube rack**<BR>
Say, you ran out of racks for your favorite 20 mm diameter test tubes, but you do have some 3mm sheet and a lasercutter around. Here you will find a design to help you out. This design features optimized (staggered!) hole placement, an elevated floor plate for extra stability and easy tube manipulation, and handles for better rack mobility. Bonus feature: holes to wire a string and create an _additional_ handle.

<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/tube-rack-3mm-200x250.png" width="250" height="313" /> &nbsp; &nbsp; &nbsp;
<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/rack-1.png" width="400" height="313" />

[Tube rack vector file](https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/tube-rack-3mm-200x250.svg "for ze lasercutter")
#
**Sterile hood**<BR>
This is an adaptation of the BioHack Academy 4 sterile hood. It features the same Ikea embedded fan, hepa filter, and pre-filter; but a novel hood. this hood needs to be placed on a sterile surface and keeps a clear acrylic sheet between your hands and your head. No more breathing on your tiny invisible friends! I printed custom hepa filter holders and also added two extra feet on the Ikea part for stability.

<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/hood.png" width="400" height="300" /> &nbsp; &nbsp; &nbsp;
<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/sterilehood.png" width="375" height="300" />

[files for cutting and printing](https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/JML_sterile_hood.zip)
# 
**Stirrer**<BR>
Building the stirrer was a bit of a challenge. I blew the led, and the heating pad seemed not to operate at all! Raza had the same issues and [solved them.](https://github.com/R4za/BiohackAcademy2017#24-02-2017---debugging-the-magnetic-stirrer) I adopted Raza's hack and got the stirrer to work. Sort of, for the next version I will use a different heating pad.
#
**Incubator**<BR>
#
**Thermocycler**<BR>
#
**Gelbox**<BR>
#
**Dremelfuge**<BR>
Someone on the internet built a dremeltool centrifuge add-on. Inspired by this, I designed one too. Mine can be 3D printed in one go, moving parts and all, without the need for assembly or scaffolding. The trick for this is to use ball and socket joints between moving parts. I spun the add-on at the dremeltool's maximum speed (35.000 rpm), and it took this without problems. Still, if you make this yourself, be safe and use it in a bucket! I glued the shaft of a 3mm diameter nail into the add-on's center hole to interface with the dremeltool. The picture to the right opens a movieclip of the tool in action. 

<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/dremelfuge.png" width="320" height="280" /> &nbsp; &nbsp; &nbsp;
<a href="https://www.facebook.com/janmaarten.luursema/videos/vb.100000127123588/1580026075344948/?type=2&theater"><img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/dremf-mov.png" width="200" height="280"/></a>

[3D files for printing and rolling your own](https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/JML_dremelfuge.zip)
<BR><BR><a href="#top">*top of page*</a>
#
# Winogradsky enclosures<a id="wgb"></a><BR>
**Winogradsky enclosure with temperature gradient**<BR>
Most micro-organisms live in complex ecological networks. The Winogradsky jar is one of the few tools available to study such networks. A Winogradsky jar is a sealed container in which a micro-organism-rich sample has been scooped, along with optional added ingredients. Under gravity, and in interaction with each other, the micro-organisms often will self-organize in distinct layers that feed on each others waste products.

To experimentally study such networks, I have added peltier modules to the sides of a rectangular Winogradsky jar (an adapted airtight, transparant food container). In this way, a temperature gradient can be introduced at a ninety degree angle relative to gravity´s vector. On top I have added two extra lids to facilitate sampling. I am now working on the electronics and programming.

<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/winobox-1.png" width="320" height="240" /> &nbsp; &nbsp; &nbsp;
<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/winobox-2.png" width="320" height="240" />
#
**Winogradsky enclosure with nutrient gradient**<BR>
Time permitted, I will start working on a second Winogradsky jar based design. This one will have a peristaltic pump on either side to allow the introduction of nutrients. Or additional microorganisms. Or harmful substances.
<BR><BR><a href="#top">*top of page*</a>
#
# Slime mold arena<a id="sma"></a><BR>
**Arena build**<BR>
The slime mold is a remarkable creature, showing intelligent behavior in the absence of a nervous system. As such, many researchers believe it can get bored and in fact it will often try to escape its enclosure looking for adventure. I designed a home that will make it easy to keep the slime mold in your life entertained, while also making it unattractive for it to wander off.

The enclosure is elevated and transparant, so you can slip pieces of paper underneath and distribute treats on the floor of the enclosure according to the markings on your paper. Your slime mold will now try to make sense of your message by connecting the dots. Some say it will do this as an artistic reflection on its place in the universe. This I consider conjecture, as an advanced being such as the slime mold surely realizes Self is defined in its relation to Other, and not by engaging in solipsist noodling.

The stage for its explorations is floating on a solidified bed of agar and salt, which it will be reluctant to cross. The lid will help maintain a damp microclimate, while keeping potential predators out. The lid has a grated opening to allow some exchange of fresh and moldy air. The grate is taken from a faucet, I included 3D printing files for the holder below. The ridge to elevate the enclosure turned out a little high, you may want to reduce it to 5mm or so.

<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/slime-mold-enclosure-3mm-acrylate-350x665.png" width="220" height="400" /> &nbsp; &nbsp; &nbsp;
<img src="https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/slime_mold_hold.png" width="500" height="400" />

[3D files for air exchange grate holder](https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/air-grate-holder-slime-mold.zip "to adapt and to print")

[Acrylate enclosure vector file](https://github.com/J4n-M44rt3n/J4n-M44rt3n_github.io/blob/master/images/slime-mold-enclosure-3mm-acrylate-350x665.svg "foor die laser cutter")
#
**Arena experiment**<BR>
Slime molds have been asked to help out with optimization problems. Such problems are computationally hard for us, but [slime molds have them for breakfast](https://www.wired.com/2010/01/slime-mold-grows-network-just-like-tokyo-rail-system/). I want to introduce the ever-curious slime mold to the field of sociology. The challenge is this: It is easy to get around by train within the Netherlands or Belgium, but very time consuming to get from place to place between those countries. I will let the slime mold forage on a map of Belgium and the Netherland, with train stations in major cities reperesented by oat flakes. I think it will faithfully reproduce the railroad network within these countries, and fastly *improve* connectivity between them. If this works out, it means that slime molds can be used to identify adversity between groups of people, by highlighting a *lack* of infrastructure that would be needed if these groups wanted to trade or share resources.
<BR><BR><a href="#top">*top of page*</a>
#
# to be continued<a id="tbc"></a><BR>
**Self-contained microfluidic devices 'ecosystem on a chip'**<BR>
#
**Gradient petri dishes for separating microbiological ecological networks**<BR>
#
**Gradient petri dishes for directional growth**<BR>
#
**Fish-eye light field microscopy**<BR>
#
**The alien within; are there messages hidden in the DNA of our biosphere?**<BR>
#
**A Charter of post-Human Rights**<BR>
I really like charters. Charters interface directly with our lifes and organizations; are *for* something and thus need to be explicit about their goals; and need to build from unambiguous, specific definitions (insofar as this is possible, definitions always being somewhat fuzzy around the edges). 

Increasingly, technology makes us face ethical dillemas that are outside the scope of our sense of morality. The consequences of the engineered changes that we will see in our bodies have been long anticipated in literature and philosophy, for instance in [Chesterton's 1909 ultrashort story 'How I Found the Superman'](http://www.cse.dmu.ac.uk/~mward/gkc/books/HIFTS.html), which features the line 'He creates his own standard, you see,' she replied, with a slight sigh. 'Upon that plane he is more than Apollo. Seen from our lower plane, of course...' And she sighed again.'.

As an exercise, I plan to work on a charter of post-human rights. To limit the potential sprawl of such an exercise, I will start trying to define post-human. First issue: does such a definition need to be established at the individual level, or at a group level? If at a group level, traditional definitions fall apart, notions of 'species' or 'culture' do not begin to cover the type of clustering we need to take into consideration. I think I will start by appropriating the word 'cluster'... 
<BR><BR><a href="#top">*top of page*</a>
#
[BioHack Academy on Facebook](https://www.facebook.com/groups/biohackacademy/)

