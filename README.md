# gatsby-plugin-gosquared

Simple plugin to add your [GoSquared](https://www.gosquared.com/) tracking snippet to a Gatsby site.

## Install
- `yarn add gatsby-plugin-gosquared`
- or `npm install --save gatsby-plugin-gosquared`

## Usage
In your gatsby-config.js file:

```js
plugins: [
  {
    resolve: `gatsby-plugin-gosquared`,
    options: {
      token: 'GSN-123456-A',
    },
  },
]
```