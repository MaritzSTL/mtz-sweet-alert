# `<sweet-alert>` - a Polymer 2 wrapper for [SweetAlert2](https://github.com/sweetalert2/sweetalert2)

[![Build Status](https://travis-ci.org/sweetalert2/sweetalert2-polymer.svg?branch=master)](https://travis-ci.org/sweetalert2/sweetalert2-polymer)
![Bower version](https://badge.fury.io/bo/sweetalert2-polymer.svg)
[![npm version](https://badge.fury.io/js/sweetalert2-polymer.svg)](https://www.npmjs.com/package/sweetalert2-polymer)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/sweetalert2/sweetalert2-polymer)

[Live demo ↗](https://sweetalert2.github.io/sweetalert2-polymer/components/sweet-alert/#/elements/sweet-alert/demos/demo/index.html)

<!--
```
<custom-element-demo height="450">
  <template>
    <link rel="import" href="sweet-alert.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<sweet-alert title="Oops..." text="Something went wrong!" type="error"></sweet-alert>

<script>
  document.querySelector('sweet-alert').open()
</script>
```

# Installation

```bash
bower install --save sweetalert2-polymer
```

# Usage

```html
<link rel="import" href="bower_components/sweet-alert/sweet-alert.html">

<sweet-alert type="success" title="Awesome"></sweet-alert>
```
