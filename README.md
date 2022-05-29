<p align="center">
  <img src="https://app.1inch.io/assets/images/logo.svg" width="200" alt="1inch network" />
</p>

# 1inch swap widget

Library for integrating `1inch swap widget`

## Test coverage

| Statements                  | Branches                | Functions                 | Lines             |
| --------------------------- | ----------------------- | ------------------------- | ----------------- |
| ![Statements](https://img.shields.io/badge/statements-92.3%25-brightgreen.svg?style=flat) | ![Branches](https://img.shields.io/badge/branches-66.66%25-red.svg?style=flat) | ![Functions](https://img.shields.io/badge/functions-80%25-yellow.svg?style=flat) | ![Lines](https://img.shields.io/badge/lines-92.3%25-brightgreen.svg?style=flat) |

## Installation

### Node

```
npm install @1inch/embedded-widget
```

### Yarn

```
yarn add @1inch/embedded-widget
```

---

## Usage
```typescript
import {setup1inchWidget} from '@1inch/embedded-widget';

setup1inchWidget({
    chainId: 137,
    sourceTokenSymbol: '1INCH',
    destinationTokenSymbol: 'DAI',
    hostElement: host,
    provider: window.ethereum,
    theme: 'light',
    sourceTokenAmount: '15'
});
```