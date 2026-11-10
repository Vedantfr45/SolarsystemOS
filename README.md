# SolarsystemOS
A solarsystem made by me and a little bit claude.

## Voyager 1 and 2

Both Voyager probes fly in the scene and can be clicked for live mission details.
The 3D model is "Voyager Probe (B)" from [NASA 3D Resources](https://github.com/nasa/NASA-3D-Resources) (NASA/JPL-Caltech, free of copyright), converted to `voyager.glb` without Draco compression so it loads with the stock three.js GLTFLoader.

## The endless zoom

Scroll out past the cosmic web and other universes appear around ours. Keep going and they all turn out to sit inside one proton, in a carbon nucleus, in an atom drifting in the Sun's plasma. Zoom out of that Sun and you are back in the Solar System. Scroll in to the Sun and the same trip runs backwards. One turn is 13 powers of ten, and it loops forever in both directions. The left-hand scale menu jumps to any stop.

Everything in the loop is drawn in code. Inspired by Charles and Ray Eames' *Powers of Ten* (1977), the closing shot of *Men in Black* (1997) and Ant-Man's Quantum Realm. The other universes are imagined; the proton, atom and Sun facts are real.

## Zoom slider and words on the way

The page opens on a single proton and invites you to zoom out. Scroll, pinch, or use the slider on the right: pull its knob up to zoom out or down to zoom in (further means faster, it never runs out, and it springs back to the middle when you let go), or hold **Out** / **In** if you have no mouse wheel. On the way out, Carl Sagan's Pale Blue Dot line appears at the bottom as Earth shrinks to a dot in the Solar System, with a couple more quotes further out, and at the multiverse, also at the bottom: "Look how small we are." The **Quotes on/off** button next to the music hides all of these and keeps only the place names; the choice is remembered.

## Music

"Purpose Is Glorious" by Natalie Holt, from the Loki Season 2 score (Marvel Studios / Hollywood Records), credited on screen with a play/pause button. Browsers block autoplay, so it starts on the first tap or key press. The track is copyrighted and not in the repo; see [assets/music/README.md](assets/music/README.md).

## The black hole at the centre of the galaxy

Zoom out to the Milky Way, then zoom in a little on the bright core: the black hole appears right there, edge-on with its disk arching over the shadow, and the core's glow fades into a dark cavity around it. **Sagittarius A\*** at its centre (or the **Black hole** button at the bottom) to fly there. It is ray traced live in a shader: every pixel follows a light ray backwards through the curved space around the hole, so the far side of the disk arching over and under the shadow, the thin photon ring, the brighter side moving toward you, and the bent Milky Way behind it are all real effects, not painted on. Drag to orbit it and scroll to get closer. Drawn far larger and brighter than the real one.
