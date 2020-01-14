# @my-design-system/babel-preset

Automatically load the css for the @my-design-system design system.

## Installation

```sh
npm i --save-dev @my-design-system/babel-preset
# or
yarn add -D @my-design-system/babel-preset
```

## Usage

.babelrc:

```json
{
  "presets": ["@my-design-system/babel-preset"]
}
```

## Example

Input:

```js
import Card from '@my-design-system/card';
```

Output:

```js
import Card from '@my-design-system/card';
import '@my-design-system/card/dist/main.css';
```
