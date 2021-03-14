# material-ripple
### Material Design Ripple Effect.

material-ripple makes you able to have Material Design Ripple Effect on the elements you want.

#### material-ripple comes with two colors:
1. Light "data-ripple-light"
2. Dark "data-ripple-dark"

## Installation
Install the material-ripple from npm.

```
npm i material-ripple
```

## Using NPM
1. Import the material-ripple in to your project.

```
import "material-input";
```

2. material-ripple works using the data attribute on the elements, set the `data-ripple-light` or `data-ripple-dark` on the element you want to have material design ripple effect.

```
import React from "react";
import "material-input";

export default function Button() {
  return (
    <button data-ripple-light={true}>Material Ripple</button>
    <button data-ripple-dark={true}>Material Ripple</button>
  );
}
```

## Using CDN
1. Add the CDN script of material-ripple in to your HTML file.

```
<script crossorigin src="https://unpkg.com/material-ripple"></script>
```

2. material-ripple works using the data attribute on the elements, set the `data-ripple-light` or `data-ripple-dark` on the element you want to have material design ripple effect.

```
<button data-ripple-light="true">Material Ripple</button>
<button data-ripple-dark="true">Material Ripple</button>
```