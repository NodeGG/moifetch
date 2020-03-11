# Moifetch

> A Lite http/https fetch built with ❤

<!-- BADGES -->

[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)](https://github.com/NodeGG/Moifetch/blob/master/LICENSE) [![Twitter Follow](https://img.shields.io/badge/follow-%40MOIKUNE-blue.svg?style=for-the-badge&logo=twitter)](https://twitter.com/MOIKUNE) [![Discord](https://img.shields.io/discord/687169639712686097?style=for-the-badge&logo=discord)](https://discord.gg/DnbkrC8) [![NPM](https://img.shields.io/npm/dt/moifetch.svg?style=for-the-badge)](https://www.npmjs.com/package/moifetch)

<!-- BADGES END -->

## Introduction

A lite Http/Https Request Library build with Love and my attempt to Homebrew something for other to use.

## How to Add

```
npm i moifetch

yarn add moifetch
```

## Examples

```
const moifetch = require('./index');
or
import moifetch from 'Moifetch'

moifetch('https://httpbin.org/get').then(res => {
  expect(res.statusCode).toBe(200);
});

moifetch('https://httpbin.org/post', { method: 'POST' }).then(res => {
  expect(res.statusCode).toBe(200);
});


moifetch('https://httpbin.org/put', { method: 'PUT' }).then(res => {
  expect(res.statusCode).toBe(200);
});

moifetch('https://httpbin.org/delete', { method: 'DELETE' }).then(res => {
  expect(res.statusCode).toBe(200);
});


```
