# 💧 plop generator react context

[![version][version-badge]][npm]
[![downloads][downloads-badge]][npm]
[![size][size-badge]][bundlephobia]
[![github actions][github-actions-badge]][github-actions]
[![coverage][codecov-badge]][codecov]
[![typescript][typescript-badge]][typescript]
[![contributing][contributing-badge]][contributing]
[![contributors][contributors-badge]][contributors]

_A [`plop`][plop] generator for [`react`][react] context._

## 📦 Installation

This package is hosted on [`npm`][npm].

```bash
npm install --save-dev @piperguy/plop-generator-react-context
```

## 🥑 Usage

First, be sure you have [`plop`][plop] installed. Then, add the following line to your `plopfile.js`.

```javascript
plop.load("@piperguy/plop-generator-react-context")
```

Now you'll have access to the `context` generator as shown below.

```bash
plop context
```

The `context` generator scaffolds a new context, including a consumer hook, and adds it to the `index.ts` file for easy importing. The resulting directory looks like this for a context named `App`.

```text
src
└── context
   ├── App.tsx
   └── index.ts
```

## ❔ Questions

🐛 report bugs by filing [issues][issues]  
📢 provide feedback with [issues][issues] or on [twitter][twitter]

[codecov]: https://app.codecov.io/gh/piperguy/plop-generator-react-context
[contributing]: https://github.com/piperguy/plop-generator-react-context/blob/master/contributing.md
[contributors]: #-contributors
[npm]: https://www.npmjs.com/package/@piperguy/plop-generator-react-context
[codecov-badge]: https://img.shields.io/codecov/c/github/piperguy/plop-generator-react-context?style=flat-square
[version-badge]: https://img.shields.io/npm/v/@piperguy/plop-generator-react-context.svg?style=flat-square
[downloads-badge]: https://img.shields.io/npm/dt/@piperguy/plop-generator-react-context?style=flat-square
[contributing-badge]: https://img.shields.io/badge/PRs-welcome-success?style=flat-square
[contributors-badge]: https://img.shields.io/github/all-contributors/piperguy/plop-generator-react-context?style=flat-square
[issues]: https://github.com/piperguy/plop-generator-react-context/issues
[twitter]: https://twitter.com/_PiperGuy_
[bundlephobia]: https://bundlephobia.com/result?p=@piperguy/plop-generator-react-context
[size-badge]: https://img.shields.io/bundlephobia/minzip/@piperguy/plop-generator-react-context?style=flat-square
[github-actions]: https://github.com/piperguy/plop-generator-react-context/actions
[github-actions-badge]: https://img.shields.io/github/workflow/status/piperguy/plop-generator-react-context/%F0%9F%9A%80%20release?style=flat-square
[typescript]: https://www.typescriptlang.org/dt/search?search=%40piperguy%2Fplop-generator-react-context
[typescript-badge]: https://img.shields.io/npm/types/@piperguy/plop-generator-react-context?style=flat-square
[plop]: https://plopjs.com
[react]: https://reactjs.org
