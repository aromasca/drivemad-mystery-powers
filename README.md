# Drive Mad: Mystery Powers

2D physics driving game with random mystery powers — built with Matter.js in a single HTML file.

Navigate tricky terrain without flipping your car! Every 8-12 seconds a random mystery power activates, adding chaos to your run.

## Mystery Powers

| Power | Effect |
|---|---|
| Slippery Wheels | Almost zero wheel friction |
| Heavy Car | 3x gravity on the car |
| Reverse Controls | Left and right are swapped |
| Bouncy! | High restitution — everything bounces |
| Slow Mo | Time slows to 40% |
| Extra Grip | Maximum wheel friction |
| Moon Gravity | 0.3x gravity — float away |
| TURBO! | Constant forward force |

## Controls

- **Arrow keys** or **touch buttons** on mobile
- Right = accelerate, Left = brake/reverse

## Tech

- [Matter.js](https://brm.io/matter-js/) for physics
- HTML Canvas for rendering
- [Astro](https://astro.build/) for static hosting via Cloudflare Pages

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```
