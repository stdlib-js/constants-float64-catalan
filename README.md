<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# CATALAN

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> [Catalan's constant][catalan-constant].

<section class="intro">

[Catalan's constant][catalan-constant] `C` (also denoted `K` or `G`) commonly appears in estimates of combinatorial functions and may be defined by the following infinite series

<!-- <equation class="equation" label="eq:catalan_constant" align="center" raw="C = \sum_{n=0}^{\infty} \frac{(-1)^{n}}{(2n+1)^2} = \frac{1}{1^2} - \frac{1}{3^2} + \frac{1}{5^2} - \frac{1}{7^2} + \cdots" alt="Catalan's constant"> -->

<div class="equation" align="center" data-raw-text="C = \sum_{n=0}^{\infty} \frac{(-1)^{n}}{(2n+1)^2} = \frac{1}{1^2} - \frac{1}{3^2} + \frac{1}{5^2} - \frac{1}{7^2} + \cdots" data-equation="eq:catalan_constant">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@6e1cf583c4854b3d982f22f361f53a30c9f552dc/lib/node_modules/@stdlib/constants/float64/catalan/docs/img/equation_catalan_constant.svg" alt="Catalan's constant">
    <br>
</div>

<!-- </equation> -->

</section>

<!-- /.intro -->

<section class="installation">

## Installation

```bash
npm install @stdlib/constants-float64-catalan
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

</section>

<section class="usage">

## Usage

```javascript
var CATALAN = require( '@stdlib/constants-float64-catalan' );
```

#### CATALAN

[Catalan's constant][catalan-constant].

```javascript
var bool = ( CATALAN === 0.915965594177219 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better example -->

<!-- eslint no-undef: "error" -->

```javascript
var CATALAN = require( '@stdlib/constants-float64-catalan' );

console.log( CATALAN );
// => 0.915965594177219
```

</section>

<!-- /.examples -->

<!-- C interface documentation. -->

* * *

<section class="c">

## C APIs

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- C usage documentation. -->

<section class="usage">

### Usage

```c
#include "stdlib/constants/float64/catalan.h"
```

#### STDLIB_CONSTANT_FLOAT64_CATALAN

Macro for [Catalan's constant][catalan-constant].

</section>

<!-- /.usage -->

<!-- C API usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- C API usage examples. -->

<section class="examples">

</section>

<!-- /.examples -->

</section>

<!-- /.c -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-float64-catalan.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-float64-catalan

[test-image]: https://github.com/stdlib-js/constants-float64-catalan/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/constants-float64-catalan/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-float64-catalan/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-float64-catalan?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-float64-catalan.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-float64-catalan/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-float64-catalan/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-float64-catalan/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-float64-catalan/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-float64-catalan/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-float64-catalan/main/LICENSE

[catalan-constant]: https://en.wikipedia.org/wiki/Catalan%27s_constant

</section>

<!-- /.links -->
