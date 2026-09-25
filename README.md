# Stretchy

Two characters, **Stretchy** and **Grumpy Sarge**, who has a cigarette that smokes. Switch between them with the avatars next to the logo, or link to one directly with `?c=sarge`.

Grab his face and pull. Let go and he springs back with a wobble. A **quick tap** (or a fast swipe) **slaps** him: his head jolts, a red handprint appears, a comic "SLAP!" pops up and the screen shakes. Two fingers stretch both cheeks at once. On desktop, the "Both hands" button mirrors your pull.

A single `index.html` built on Three.js from a CDN, with no build step. His face is one frame (`media/face.jpg`) from the source video. It sits on a dense mesh, and a vertex shader bends that mesh around up to 4 grabs. Each grab has its own spring, which gives the snap-back.

Run it locally with `python -m http.server` inside this folder, then open http://localhost:8000.
