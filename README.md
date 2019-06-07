# Typescript Perlin Noise

Typescript reference implementation of improved noise.

## Usage

Use the normal class.

```ts
import { Perlin } from "./Perlin";

let perlin: Perlin = new Perlin();

// 1D Perlin Noise
perlin.noise(x);

// 2D Perlin Noise
perlin.noise(x, y);

// 3D Perlin Noise
perlin.noise(x, y, z);
```

Or use the static class.

```ts
import { Perlin } from "./static/Perlin";

// 1D Perlin Noise
Perlin.noise(x);

// 2D Perlin Noise
Perlin.noise(x, y);

// 3D Perlin Noise
Perlin.noise(x, y, z);
```

Personally, I prefer the static class, but it's completely up to you. They both do the same.