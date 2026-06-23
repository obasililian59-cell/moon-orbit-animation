# moon-orbit-animation

A responsive CSS animation that simulates the moon orbiting around Earth using pure HTML and CSS.

🌠 What It Does : 

- Earth positioned at the center of the screen.
- Moon orbits smoothly using CSS transforms.
- Subtle star background with twinkle animation.
- Responsive adjustments for smaller screens.

🔧 How It Works: 

Orbital Motion
The moon orbits using a combination of:
- `translateX(150px)` — sets the orbital distance.
- `rotate(0deg → 360deg)` — creates the circular path.
- `transform-origin: -150px 0` — shifts the pivot point so rotation happens around Earth.

Centering
Both Earth and Moon are centered using:
```css
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
```

Responsive Fix :
On smaller screens (max-width: 400px), the orbit distance is reduced to prevent the moon from orbiting inside Earth.

🌌 Atmosphere :
- Earth glow created using layered `box-shadow`.
- Stars created using `box-shadow` on a pseudo-element.
- Twinkle effect using opacity animation.

🖥️ Live Demo:
https://obasililian59-cell.github.io/moon-orbit-animation/

🛠️ Built With
- HTML5
- CSS3
- CSS Animations & Keyframes
