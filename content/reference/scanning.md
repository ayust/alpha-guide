{
  "date": "2016-11-18T18:56:39-08:00",
  "prev": "/reference/",
  "title": "Scanner Probes And You",
  "toc": "true",
  "weight": "1"
}

This guide is an alternative to the in-game scanning tutorial video (though you can also watch that
by pressing <kbd>F12</kbd> and going to the Tutorial Videos tab, Exploration section).

### What Are Probes For, Anyway?

Many sites in EVE, such as Stations and Stargates,
show up on your Overview so that you can warp to them from anywhere.

Others, such as Mission deadspace pockets, don't show up on your Overview, but you're given
co-ordinates for them, so you can warp to them directly without needing to find them.

But some sites are hidden, and require special tools and some effort to find.
These "Cosmic Signatures" can only be found via the use of Scanner Probes,
and offer valuable rewards and unique opportunities.

There are five types of Cosmic Signature:

 * Relic sites, which give valuable salvage and construction materials
 * Data sites, which give datacores and rare blueprints
 * Gas sites, which have rare gas clouds used for drug production or advanced ship manufacturing
 * Combat sites, difficult "dungeons" which can drop rare and valuable Faction and Deadspace modules
 * Wormholes, which are [worthy of their own topic](/reference/wormholes/)

Searching for Relic and Data sites is a good way to make money as a new player.
It can be a bit of a lottery, finding nothing for hours one day and hitting the
jackpot within five minutes the next.  The great rewards from nullsec and wormhole-space
Relic and Data sites can hugely enrich those brave enough to venture into
those dangerous areas - and cunning enough to make it back alive.

### Equipment

You'll need a `Core Probe Launcher I` loaded with 8x `Core Scanner Probe I`.
You'll also probably want a `Data Analyzer I` and a `Relic Analyzer I`
to be able to access the riches you find, and an Afterburner or Microwarpdrive
to fly around between the reward "cans" more easily.

### Setting Up

First, you'll need to find a Cosmic Signature.  Open your probe scanner.
You can press <kbd>Alt</kbd>+<kbd>P</kbd>, or get to it through the Scanners button on your HUD:

<video autoplay loop muted>
  <source src="/images/openscanner.webm">
  <source src="/images/openscanner.mp4">
</video>

That'll open your Probe Scanner window.  If you're in a starter system
(for example, if you're looking at this for help with Exploration (3 of 5)),
you probably have a *lot* of things showing; in other systems, it'll be rather more sparse.

We're trying to scan things down with our probes.  That means we're not interested in
Cosmic Anomalies - those are also found via the Probe Scanner, but don't require
any probes to find.  They're a separate kind of site, and not what we're after.

To filter out this Cosmic Anomaly clutter, use the filter options by "Scan Results":

<video autoplay loop muted>
  <source src="/images/filteranoms.webm">
  <source src="/images/filteranoms.mp4">
</video>

Now, open your Starmap to see a map of the system:

{{% figure src="/images/openstarmap.png" %}}

If there's many Cosmic Signatures in system, the solar system map is probably going to look
like a bit of a confusing mess.  You can click on a Cosmic Signature from the list, to show only that one
and hide the others.  (It doesn't matter which Cosmic Signature you start with - there's
no way to tell them apart at this point in the process.)

<video autoplay loop muted>
  <source src="/images/selectsig.webm">
  <source src="/images/selectsig.mp4">
</video>

<video autoplay loop muted>
  <source src="/images/selectsigstarmap.webm">
  <source src="/images/selectsigstarmap.mp4">
</video>

Now, click one of the buttons at the top of the Probe Scanner to deploy your Probes.
I prefer to use the Pinpoint Formation at all times; you can create your own formations,
or switch between them as you go, but for now just stick with Pinpoint.
Clicking the button will deploy a probe formation centered on the system's star:

{{% figure src="/images/launchprobes.png" %}}

<video autoplay loop muted>
  <source src="/images/launchprobesstarmap.webm">
  <source src="/images/launchprobesstarmap.mp4">
</video>

The actual probes will be floating in space next to your ship - 
their location on the Starmap indicates their planned location for the next scan.

Now that we've got the starmap filtered down to something a bit more manageable,
you should know how to read the map before moving on.

### Using The Solar System Map

To swivel your camera, click-and-drag the left mouse button.

To pan the camera, click-and-drag the right mouse button.

To re-center the camera on a point in space, double-click on an icon
(such as a station, or most usefully, the cube representing the center of your probe formation).

To zoom in or out, use the scrollwheel, or click-and-drag with both mouse buttons simultaneously.

Your ship appears as a small crosshair icon on the starmap.  Its position is relatively unimportant
for scanning, so ignore it.

The rest of the system shows the orbitals of the planets, stargates, stations, and other celestial
objects around the star.  This is of great use for the Directional Scanner.

Our primary point of interest is the large red sphere we see, with a red "X" in the center.
That's our ship's approximate fix on the Cosmic Signature's location; it's very rough and
imprecise, however, which is why we have probes to narrow it down.

The Cosmic Signature is **almost certainly not at the X**.  Instead, it's somewhere on the surface of
that red sphere.  Our job, with the probes, is to find out exactly where.

To do this, we're going to first **isolate the signature**, then **enhance the precision**.

### Isolate The Signature

{{% notice info %}}
The first parts of this guide were written in a starter system, with many of the tutorial signatures.
The remainder was written in another system, as the more difficult signatures
outside of the starter system provide a better example of the steps taken to isolate a signature.
{{% /notice %}}

As a first step, drag the center of your probe formation (the gray box in the center, with arrows
on each face) to the X's position, to center your probes.  Make sure to rotate your view
on the starmap (click-and-drag on any open space) to make sure that you're centered in 3D,
not just in a straight line behind it from your camera position.

You can either click-and-drag a face of the cube to move in a plane, or click-and-drag
an arrow to move in a straight line.

<video autoplay loop muted>
  <source src="/images/centerprobes.webm">
  <source src="/images/centerprobes.mp4">
</video>

As mentioned earlier, the signature is probably not at the red X - so we want to expand our probes'
scan area, to cover as much of the sphere's area as possible (ideally, the entire thing).
You can do this in one of three ways:

 * Go to the "Probes" section of your Probe Scanner.  Select all the probes,
 either by clicking on one and then pressing <kbd>Ctrl</kbd>+<kbd>A</kbd> or by
 clicking the top Probe and holding Shift as you click the bottom Probe.
 (You may need to expand the top section of the window to be able to see all probes.)
 Then, right-click on a Probe and select the desired Scan Radius.
 * Click-and-drag on an edge of the blue sphere representing the probes' scan radius in the Starmap,
 releasing at the approximate desired radius.  They will snap to the setting closest to where
 you release.
 * Hold Alt to show arrows for the directions of the individual probes relative to the center
 of the formation.  Click-and-drag outwards on one of the arrow heads, releasing at the approximate
 desired radius.  They will snap to the setting closest to where you release.
 
Either way, it can be worth swivelling the camera on the Starmap to ensure you're fully covering the target.
Note that you probably want the **overlapping area at the center** of your formation to be
covering the whole sphere, not just one probe's area - the reason will become clear later.

<video autoplay loop muted>
  <source src="/images/expandprobes.webm">
  <source src="/images/expandprobes.mp4">
</video>

Once your probes are in position and set to the proper radius, click "Analyze", at the upper left of
your starmap.  Your probes will warp to their designated positions, and begin the scan,
taking approximately 10 seconds.

When the scan finishes, there are a couple different things you might see.
To understand what they mean, let's take a little look at what the probes are doing.

#### Triangulation - In Space!

The theory of the probe scanner is essentially the same as triangulating a position on Earth.
Since we're working in 3D space, it's actually quadrangulating, but uses the same principles.

Each probe internally reports an estimated distance to the signature's location,
but has no sense of direction.  (There's no way to see this estimated distance
for a given probe directly, it's just used in the next steps.)

In order to combine the probes' distance readings and get a definite fix on the location,
you need to have **at least four probes** in range of the signature when you scan.
So long as the probes are arranged in a formation that surrounds the signature,
this allows them to combine their results and conclude a single position where
the signature must be.

If you only get a hit with three or fewer probes, they won't have enough information
to narrow it down to a single position:  there's multiple places it could be,
all of which would have generated the same result.  If this is the case,
the map shows all possible locations where the signature *might* be:

 * If only one probe got a hit, it will show a red sphere around that probe,
 at the estimated distance, as your only information is "it is a certain distance from that probe".
 The signature is somewhere on the surface of that sphere (NOT at the X in the center).
 
 {{% figure src="/images/redsphere.png" %}}
 
 * If two probes got a hit, it will show a dashed red circle where their scan areas overlap - 
 all points on that circle match the distance readings from both probes.
 The signature is somewhere on the rim of that circle (NOT at the X in the center)
 
 {{% figure src="/images/rrod.png" %}}
 
 * If three probes got a hit, it will show **two** dots.
 The signature is at one of those two positions.
 The other one contains nothing - it's a false echo.
 
 {{% figure src="/images/twodots.png" %}}
 
 * If all four probes got a hit, it will show **one** dot.
 This is what you want!
 
 {{% figure src="/images/onedot.png" %}}

If you got anything other than a single dot, spend some time now
dragging around your probes and re-scanning, focusing on the positions it may potentially be:
the surface of the sphere or circle, or one of the two dots.

If you simply can't seem to isolate the signature beyond a sphere/ring, or if you lose it
completely (no change in reported position, and/or "No scan signatures detected" message), 
consider starting over - re-center your probes on the red X,
expand their scan radius to cover the entire red sphere/ring, and begin the process again.

Once you have a result that only shows a single dot, move on to the next step.

{{% notice info %}}
As there is some inaccuracy in the distance reported by the probes (their "Base Maximum Deviation" attribute),
the position reported is inaccurate as well, and will "jump around" with successive scans
until the signature is fully probed down.  This is normal - just keep chasing the new reported position.
{{% /notice %}}
 
### Enhance The Precision

At a wide radius, your probes cover a lot of ground, but their sensors are weak and imprecise.
This is good for initially finding the target, but now that you're found a rough location for the signature,
it's time to enhance the precision.

If you look over at your Probe Scanner, the Cosmic Signature should have a number in the "Signal" field - 
probably pretty low, from this wide initial hit.  **Your objective is to get the Signal to 100%.**

Your best tool for doing this is progressively narrower scans.  Each time you halve the radius of
your scanner probes, their power doubles.

To get a stronger hit, pretend like it's CSI: zoom in, and enhance.  

Lower the radius of your probes by one step (to half of what it was), position
them over the estimated position of the signature, and scan again.  (It'll be helpful
to recenter your camera on the estimated position, by double-clicking it, and zoom in with the scrollwheel.)

Remember to check the position from multiple angles!

<video autoplay loop muted>
  <source src="/images/zoominenhance.webm">
  <source src="/images/zoominenhance.mp4">
</video>

### Lather, Rinse, Repeat

At this point, getting the signature to 100% is just a matter of repeating the steps you already know:

 * Isolate the signature to a solid, single-dot hit
 * Re-center probes over the dot
 * Reduce scan radius
 * Scan again

Each time you repeat the process, you should have a higher Signal Strength on the Signature.
As you get closer to a full scan, you'll get more information about what type of site it is:

 * At 25%, you will learn the site's category (Data, Relic, Gas, Combat, Wormhole)
 * At 75%, you will learn the site's full name

At 100%, you'll get an arrow in the Probe Scanner for that signature, letting you warp to it.
You should right-click on the Cosmic Signature's entry in the Probe Scanner and "Save Location",
so that you don't lose it when you go to scan other areas.

When you've scanned down and bookmarked all the signatures of interest in the system,
warp to them and enjoy your loot!  The Data and Relic hacking minigame won't be covered here;
if you've found the site at all, that's a victory in itself.

Your probes' minimum scan radius is 0.25 AU.  If you've repeated the process all the way down to 
0.25 AU and still don't have a 100% hit, the signature may be too difficult to find
with your current skills, equipment, and/or ship.

### Those Last Lousy Few Percent

If you're at minimum scan radius, you're centered around the hit, and you're still below
about 70%, there's probably nothing much you can do about it - it's simply too tough
for you to fully scan down.

If you're at about 90% or above, though, there are a few tweaks you can make to help
you squeak out a tiny bit more strength for a victory.  They're not very helpful
for isolating a hit - indeed, they can make things harder - but can grant a little extra
strength in the refining and enhancement of the final hit.


 * Hold Ctrl to show all the probes' positions and distances from the center. 
 Click-and-hold on one and drag inwards towards the center of the formation.
 This will rescale the entire formation more tightly around the center.
 Try going in about halfway from their starting positions.  Adds about 5-10% strength.
 
<video autoplay loop muted>
  <source src="/images/tighterprobes.webm">
  <source src="/images/tighterprobes.mp4">
</video>
 
 * Hold Shift and it'll show the location of each individual probe in the formation, rather
 than just the formation's center.  Rearrange them into a cube with its corners surrounding the signature
 (and no probe directly on top of it at the center).  Adds about 5-10% strength.
 
<video autoplay loop muted>
  <source src="/images/timecube.webm">
  <source src="/images/timecube.mp4">
</video>
 
 * Or, you can do both.  Adds about 10-15% strength.

For constructing the cube formation, it's probably easiest to arrange them such that
the arrows pointing from each face are touching point-to-point, rather than trying
to eyeball it at longer distance.  Once you've made it, consider saving the formation for future use:
mouse over the third button near "Analyze" in your Probe Scanner, click the "Save Current Formation"
button that appears above, select a name, and save.

<video autoplay loop muted>
  <source src="/images/saveformation.webm">
  <source src="/images/saveformation.mp4">
</video>

### Tips And Tricks

You'll start to get a more intuitive feel for some of the process as time progresses,
but there's a few things you can try to keep in mind to save some time.

When trying to isolate the signature, you can sometimes rule out some
areas of the possible area.  Try to think about what areas your probes are already covering.
For example, if you have a "two-dot" hit, and one of the two dots is in the
center of your probe formation, it's probably not at that one - after all,
if it was there, your other probes would have picked it up, and it wouldn't *be*
a two-dot hit!  Try the further-away one first, instead.

Though it's not as precise, the same principle applies to sphere or ring hits.
While it's more an art than a science, as a first approximation, you should
try sections of the possible area **furthest from the center of your probe formation** first.

When setting up the initial probe scan, it is useful to note that Cosmic Signatures will
**always spawn within 4AU of an existing celestial**.  Look for sections of the sphere that come
relatively near celestials, if most of it is far away.

### Go Forth And Scan

The scanning interface can be quite bewildering at first - but the rewards
from mastering it can be great.  Hopefully by now you have a working understanding
of the process and theory of scanning.  If it seems like your bag of tea,
consider looking into our [wormhole guide](/reference/wormholes),
as strong scanning skills are essential for wormhole work.
Or, just explore around and see what you can find.  If you do find items
of value, remember to periodically dock and sell it or store it for later;
try not to keep too much value in your cargohold at any one time.

Enjoy your newfound freedom to explore the stars.  All these worlds are yours!
