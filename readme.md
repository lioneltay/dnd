[![Build Status](https://travis-ci.org/lioneltay/react-dnd.svg?branch=master)](https://travis-ci.org/lioneltay/react-dnd)

# WARNING

This package is still in development stages and the API will most likely change. The package also uses React Hooks which are still in alpha.

# Drag and Drop for react

## Install

```
npm install @tekktekk/react-dnd
```

## Issues

- [ ] mobile touch? (chess demo doesn't seem to work)

## Todo

- [ ] Add TravisCI

- [ ] Performance (review, also just see whether examples perform well)

  - [ ] should component update equivalent for hooks or else a pattern
    - [ ] want to avoid having to define the jsx is it is not needed (so probably cant use a hook)
    - [ ] you can return the same jsx with referential equality and react will avoid re rendering

- Examples

  - [x] Type demo, bins and items (recycling)
  - [ ] Drag and drop reorderable list
  - [x] Drag and drop moving a single item around

- [ ] publish to npm

  - [x] Add author to package.json
  - [x] add keywords to package.json

- [ ] write tests

- [ ] Write usage documentation

- [x] Publish documentation website on github pages

- [ ] Put examples on code sandbox

  - [ ] tweet with @codesandbox to get viewed and maybe chosen

- [ ] Introductory Blog Post
  - [ ] Twitter link

* [ ] have a look at https://github.com/mzabriskie/react-draggable
