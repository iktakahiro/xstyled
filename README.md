<h1 align="center">
  <img src="https://raw.githubusercontent.com/gregberge/xstyled/master/resources/xstyled-logo.jpg" alt="xstyled" title="xstyled" width="300">
</h1>
<p align="center" style="font-size: 1.2rem;">A utility-first CSS-in-JS framework built for React.</p>

[![License](https://img.shields.io/npm/l/@xstyled/styled-components.svg)](https://github.com/gregberge/xstyled/blob/master/LICENSE)
[![npm package](https://img.shields.io/npm/v/@xstyled/styled-components/latest.svg)](https://www.npmjs.com/package/@xstyled/styled-components)
[![npm downloads](https://img.shields.io/npm/dm/@xstyled/styled-components.svg)](https://www.npmjs.com/package/@xstyled/styled-components)
[![CircleCI](https://circleci.com/gh/gregberge/xstyled.svg?style=svg)](https://circleci.com/gh/gregberge/xstyled)
[![codecov](https://codecov.io/gh/gregberge/xstyled/branch/master/graph/badge.svg)](https://codecov.io/gh/gregberge/xstyled)
![Code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)
[![Dependencies](https://img.shields.io/david/gregberge/xstyled.svg?path=packages%2Fstyled-components)](https://david-dm.org/gregberge/xstyled?path=packages/styled-components)
[![DevDependencies](https://img.shields.io/david/dev/gregberge/xstyled.svg)](https://david-dm.org/gregberge/xstyled?type=dev)
[![Small size](https://img.badgesize.io/https://unpkg.com/@xstyled/styled-components/dist/xstyled-styled-components.min.js?compression=gzip)](https://unpkg.com/@xstyled/styled-components/dist/xstyled-styled-components.min.js)

```bash
npm install @xstyled/styled-components styled-components
```

## [Docs](https://xstyled.dev)

**See the documentation at [xstyled.dev](https://xstyled.dev)** for more information about using xstyled!

Quicklinks to some of the most-visited pages:

- [**Getting started**](https://xstyled.dev/docs/getting-started/)
- [Motivation](https://xstyled.dev/docs/motivation/)
- [System](https://xstyled.dev/docs/system/)

## Example

```js
import styled from '@xstyled/styled-components'

const Box = styled.div`
  background-color: primary; /* ⟶ theme.colors.primary */
  margin: 2; /* ⟶ theme.space.2 */
`

export default Box
```

## License

Licensed under the MIT License, Copyright © 2019-present Greg Bergé.

See [LICENSE](./LICENSE) for more information.
