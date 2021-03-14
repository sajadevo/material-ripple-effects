# material-ripple-effects
### Material Design Ripple Effects.

material-ripple-effects makes you able to have Material Design Ripple Effect on the elements you want.

#### material-ripple-effects comes with two colors:
1. Light "data-ripple-light"
2. Dark "data-ripple-dark"

## Installation
Install the material-ripple-effects from npm.

```
npm i material-ripple-effects
yarn add material-ripple-effects
```

## Using NPM or Yarn
1. Import the material-ripple-effects in to your project.

```
import "material-ripple-effects";
```

2. material-ripple-effects works using the data attribute on the elements, set the `data-ripple-light` or `data-ripple-dark` on the element you want to have material design ripple effect.

```
import React from "react";
import "material-ripple-effects";

export default function Button() {
  return (
    <>
      <button data-ripple-light={true}>Material Ripple</button>
      <button data-ripple-dark={true}>Material Ripple</button>
    </>
  );
}
```

## Using CDN
1. Add the CDN script of material-ripple-effects in to your HTML file.

```
<script crossorigin src="https://unpkg.com/material-ripple-effects"></script>
```

2. material-ripple-effects works using the data attribute on the elements, set the `data-ripple-light` or `data-ripple-dark` on the element you want to have material design ripple effect.

```
<button data-ripple-light="true">Material Ripple</button>
<button data-ripple-dark="true">Material Ripple</button>
```
