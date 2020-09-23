# React Tidy

A collection of atomic, independent, typed, tested and documented React custom hooks.

[![Bundle size](https://img.shields.io/bundlephobia/minzip/react-tidy?style=flat-square)](https://bundlephobia.com/result?p=react-tidy)
[![Tests Status](https://img.shields.io/github/workflow/status/webneat/react-tidy/Tests?style=flat-square)](https://github.com/webneat/react-tidy/actions?query=workflow:"Tests")
[![Coverage Status](https://img.shields.io/coveralls/github/webNeat/react-tidy/master?style=flat-square)](https://coveralls.io/github/webNeat/react-tidy?branch=master)
[![Rank](https://img.shields.io/librariesio/sourcerank/npm/react-tidy?style=flat-square)](https://libraries.io/npm/react-tidy)
[![Version](https://img.shields.io/npm/v/react-tidy?style=flat-square)](https://www.npmjs.com/package/react-tidy)
[![MIT](https://img.shields.io/npm/l/react-tidy?style=flat-square)](LICENSE)

## Contents

- [What is React Tidy?](#what-is-react-tidy)
- [Features](#features)
- [Installation](#installation)
- [List of Custom Hooks](#list-of-custom-hooks)
- [Contributing](#contributing)

## What is React Tidy?

**React Tidy** is a library of utility custom hooks. It's like [lodash](https://lodash.com/) for React hooks. The goal is to provide a collection of tiny hooks that solve common problems or make writing React components easier.

## Features

To keep the library **tidy**, all included hooks are:

- **Atomic**: only does **one thing** and does it well.
- **Independent**: does not depend on any external library/configuration/context to work. Just import and call it.
- **Typed**: can infer the type of its arguments and give the correct type in return.
- **Tested**: has meaningfull tests that cover all uses cases.
- **Documented**: has it's own README describing the arguments, return and giving a usage example.

## Installation

Install using `npm`

```
npm install react-tidy
```

Or using `yarn`

```
yarn add react-tidy
```

## List of Custom Hooks

- [useIsMounted](src/useIsMounted) Avoid using/updating state of unmounted components.
- [useRefresh](src/useRefresh) Rerender your React component whenever you want.
- [useStorage](src/useStorage) read and write items on browser storages the React way.

## Contributing

You can contribute to this library in many ways, including:

- **Reporting bugs**: Simply open an issue and describe the bug. Please include a code snippet to reproduce the bug, it really helps to solve the problem quickly.

- **Suggesting new hooks**: If you have a common use case that you think worth having its own hook, open an issue and we will discuss it. Do you already have an implementation for it? great, make a pull request and I will review it. Please make sure your code is consistent with the rest of the codebase and use [Prettier](https://prettier.io/) to format it.

Those are just examples, any issue or pull request is welcome :)
