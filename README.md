# BlanQSlate
A simple CSS reset that includes removal of default input styling.

<img src="https://raw.githubusercontent.com/jonathanharrell/blanq-slate/master/blanq-slate.png" alt="BlanQSlate" width="250" height="250" />

Based on [MiniReset.css](https://github.com/jgthms/minireset.css). Introduces some modifications and additionally removes default styling from button and input elements.

* Sets border-box box sizing
* Resets margins and padding
* Normalizes font size to browser font size
* Sets responsive media elements
* Resets table spacing
* Removes default styling from button and input elements

## Install

```sh
npm install blanq-slate
```

Or download/clone the repo.

## Usage

Include full or minified version in the head:

```html
<link rel="stylesheet" href="node_modules/blanq-slate/blanq-slate.css">
<link rel="stylesheet" href="node_modules/blanq-slate/blanq-slate.min.css">
```

or import through css:

```css
@import '../node_modules/blanq-slate/blanq-slate.css';
```

BlanQSlate is designed to make it easier for you to write your own styling. Wherever possible, default browser styles have been removed. In some cases, this may cause parts of certain input elements to become invisible. It's up to you to write basic styles that will properly display these inputs.
