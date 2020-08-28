## Big stuff

You would be forgiven for thinking that I'm just gradually buying everything in the Eleshop and Batterfly catalogues...

### Soldering irons

#### Words of advice

Choosing a soldering station is like choosing a computer or a car.
Everybody has their own needs/preferences/constraints, nobody has
perfect information, and well-intentioned advice is clouded by
confirmation bias and brand loyalty and different requirements.

Sorry, you probably won't be able to make the perfect decision about
what equipment to buy and when, and you just have to make the best of
the situation.

I would suggest doing your research with your expected use cases
firmly in mind. If you're interested in fine SMT micro-soldering then
consider a station that is compatible with a slim and precise
handpiece. Be sure to check out the range and information at Eleshop.

#### My stuff

I splurged on a JBC
[DDPE-2QB](https://www.jbctools.com/ddpe-2-tools-dde-precision-station-product-1630.html)
micro ("precision") station plus a [JBC NASE
2C](https://www.jbctools.com/nase-2-tools-nano-rework-station-product-929.html)
nano station. This is the soldering station equivalent of a
top-of-the-line Macbook Pro i.e. expensive and luxurious and probably
overkill.

These JBC stations provide me with four tools that I can pick up and
use immediately at any time:

- [T210-A](https://www.jbctools.com/t210-a-precision-purpose-handle-product-48.html) 20W micro iron. Good for general SMT work. I use e.g. 1.6mm spoon and 0.3mm pencil tips.
- [NT115-A](https://www.jbctools.com/nt115-a-nano-handle-product-1351.html) 7W nano iron. Great for 0402/0201/01005 and any fine work in tight spaces. I use e.g. 1mm spoon and 0.1mm pencil tips.
- [AM120-A](https://www.jbctools.com/am120-a-adjustable-micro-tweezers-product-1489.html) 20W micro tweezers. Great for reworking chips by picking up e.g. SOP8 parts and placing them back while simultaneously soldering/desoldering.
- [AN115-A](https://www.jbctools.com/an115-a--product-1488-category-5-menu-1.html) 7W nano tweezers. Great for reworking passives by picking up soldered 0603/0402/0201/01005 parts and moving them around. I use the foot pedal to activate them only when heat is needed.

(Special about the JBC is that the tools feel "always on" but they
actually power down when you return them to their stands. Picking one
up turns on the heater which rises to soldering temperature within
about two seconds and that is pratically instantaneous. This suits me
well because I want to have a lot of tools available but I don't want
them all idling at high temperature for hours on end.)

I also have an 80W Ersa Nano (~$250) when I need more grunt e.g. to
clean up a large ground pad like the one under the USB controller on a
Glasgow board. I power this up when needed. I like this station but
compared with the JBC it has a large handpiece, it takes longer to
heat up (~20s vs ~2s), it's harder to change tips, and the sleep mode
is less foolproof. I also need to run this around 35C degrees hotter
than the JBC because it doesn't seem to deliver heat as smoothly into
the joint but rather relies on the tip to buffer up extra heat.

I have a Hakko 888D (~$100) that was my first iron and I don't use it
much. The handpiece is much bigger even than the Ersa, it has no
auto-sleep function meaning it runs full-blast all the time (and all
night if you forget to turn it off), it takes a long time to heat up,
and it takes me about ten minutes to cool down for changing tips
safely. It served me well early on though, especially thanks to cheap
knock-off tip sets being available to learn and experiment with.

### Hot air gun

Quick 861DW hot air rework station. Cost around $300 from Batterfly.
Seems expensive but quality seems to be excellent. I bought some bent
tips from Aliexpress that are nice for blowing heat vertically while
working under a microscope with limited space.

Chose mostly based
on [review by Louis
Rossmann](https://www.youtube.com/watch?v=ChujyTV-HME). He seems to
now think the [Atten
ST-862D](https://www.youtube.com/watch?v=wYCmU6jMLo8) is equally good
for potentially a better price.

I have looked at the fancy JBC hot air guns but for now I'm not
tempted. They have nice features like being controlled by a
thermocouple to heat and protect specific parts according to thermal
profile rules, but that's just not something I feel the need for in
the foreseeable future. I'm happy with my Quick.


### Microscope

Eakins trinocular from Aliexpress with articulating arm. (AmScope
clone.) $350 + $150 shipping. Expensive but absolutely worth every
penny!

Chose this based on the [review by Steve
Gardener](https://www.youtube.com/watch?v=B0wRdJRzPUI) and many other
satisfied customers on YouTube and eevblog forum.

Genuine AmScope were more expensive, really hard to buy from Sweden,
often bundled with impractical mounts, and people online seemed to
like the Eakins better anyway.

I also have the Eakins auto-focus camera that Steve Gardner and Dave
Jones raved about in Youtube videos. I don't really like it. The
autofocus seems gimmicky and the UI is clunky. I'd prefer to have
spent the money on a camera with higher resolution and larger sensor.

### Preheater

I have ordered a Hakko FR-830 air preheater. I haven't received it
yet. My plan is to use it together with a Stickvise elevated with a
Hakko Omnivise.

I have previously bought a Yihua 853A preheater based partly on [Steve
Gardner's positive
review](https://www.youtube.com/watch?v=mHrLQ48zfOQ). However, I don't
enjoy using it at all, it's simply too large and clumsy.

My current use case for preheating is soldering and reworking BGAs or
chips with large ground pads (e.g. USB controller on Glasgow.) I don't
like working on a cold board with the hot air gun because I need to
push a lot of heat and it dissipates across the cold board.

(My future use case for preheating is for "soaking" PCBs before
putting them into a DIY vapor phase oven. More on that soon.)

### ESD mat

I have a [120x60cm ESD
mat](https://www.digikey.com/product-detail/en/scs/8900/SCP774-ND/9606803)
with a grounding wristband. This covers the surface of my desk and can
handle a fair amount of punishment. (I've learned not to do hot air
rework directly on the pad -- it survives but it doesn't look happy.)

I don't generally use the grounding wristband but rather rely on the
mat itself to dissipate any static electricity.

I value the peace of mind to know that I'm not damaging chips with
static electricity when I work with them. I would hate to always live
with doubts about this while I am troubleshooting hard problems.

### Fume extractor

I have a [Quick 6101A1](https://quick-global.eu/produkt/quick6101a1/)
fume extractor ([~$470 from
Eleshop](https://eleshop.eu/quick-6101a1.html) to suck fumes directly
into a HEAP filter via a hose that's pointed right where I'm working.
I also have a [Levoit LV-H133 (~$235 from
Amazon)](https://www.amazon.de/Levoit-HEPA-Kombifilter-Aktivkohlefilter-3-Stufen-Filterung-Luftqualit%C3%A4tssensor/dp/B07FTB9BVS/ref=sr_1_3)
HEPA filter for the whole room to catch the fumes that escape.

I think that the best solution would be simply to solder with a fan
blowing fumes out of an open window. This doesn't work for me due to
room layout and climate. Since I'm soldering in a home office my kids
nearby I decided to err on the side of caution with two big filters.

I started with a cheap fume extractor from Aliexpress similar to [this
one](https://www.aliexpress.com/item/33015679872.html). I don't
recommend these because they take up a lot of space on the desk and
they don't move very much air. I'd much prefer a fan to blow fumes
away from my face and then a window or small room filter instead.

See also [Louis Rossmann: a word on soldering and fume extraction](https://www.youtube.com/watch?v=KAaM0z9JjYc).

