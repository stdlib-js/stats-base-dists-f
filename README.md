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

# Fisher's F

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> Fisher's F distribution.

<section class="installation">

## Installation

```bash
npm install @stdlib/stats-base-dists-f
```

</section>

<section class="usage">

## Usage

```javascript
var f = require( '@stdlib/stats-base-dists-f' );
```

#### f

Fisher's F distribution.

```javascript
var dist = f;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pdf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, d1, d2 )`][@stdlib/stats/base/dists/f/cdf]</span><span class="delimiter">: </span><span class="description">F distribution cumulative distribution function.</span>
-   <span class="signature">[`pdf( x, d1, d2 )`][@stdlib/stats/base/dists/f/pdf]</span><span class="delimiter">: </span><span class="description">F distribution probability density function (PDF).</span>
-   <span class="signature">[`quantile( p, d1, d2 )`][@stdlib/stats/base/dists/f/quantile]</span><span class="delimiter">: </span><span class="description">F distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`entropy( d1, d2 )`][@stdlib/stats/base/dists/f/entropy]</span><span class="delimiter">: </span><span class="description">F distribution differential entropy.</span>
-   <span class="signature">[`kurtosis( d1, d2 )`][@stdlib/stats/base/dists/f/kurtosis]</span><span class="delimiter">: </span><span class="description">F distribution excess kurtosis.</span>
-   <span class="signature">[`mean( d1, d2 )`][@stdlib/stats/base/dists/f/mean]</span><span class="delimiter">: </span><span class="description">F distribution expected value.</span>
-   <span class="signature">[`mode( d1, d2 )`][@stdlib/stats/base/dists/f/mode]</span><span class="delimiter">: </span><span class="description">F distribution mode.</span>
-   <span class="signature">[`skewness( d1, d2 )`][@stdlib/stats/base/dists/f/skewness]</span><span class="delimiter">: </span><span class="description">F distribution skewness.</span>
-   <span class="signature">[`stdev( d1, d2 )`][@stdlib/stats/base/dists/f/stdev]</span><span class="delimiter">: </span><span class="description">F distribution standard deviation.</span>
-   <span class="signature">[`variance( d1, d2 )`][@stdlib/stats/base/dists/f/variance]</span><span class="delimiter">: </span><span class="description">F distribution variance.</span>

</div>

<!-- </toc> -->

The namespace contains a constructor function for creating a [Fisher's F][f-distribution] distribution object.

<!-- <toc pattern="*ctor*"> -->

<div class="namespace-toc">

-   <span class="signature">[`F( [d1, d2] )`][@stdlib/stats/base/dists/f/ctor]</span><span class="delimiter">: </span><span class="description">F distribution constructor.</span>

</div>

<!-- </toc> -->

```javascript
var F = require( '@stdlib/stats-base-dists-f' ).F;

var dist = new F( 2.0, 4.0 );

var y = dist.cdf( 0.5 );
// returns ~0.36
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils-keys' );
var f = require( '@stdlib/stats-base-dists-f' );

console.log( objectKeys( f ) );
```

</section>

<!-- /.examples -->


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

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-f.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-f

[test-image]: https://github.com/stdlib-js/stats-base-dists-f/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/stats-base-dists-f/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-f/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-f?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-f.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-f/main

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-f/main/LICENSE

[f-distribution]: https://en.wikipedia.org/wiki/F_distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/f/ctor]: https://github.com/stdlib-js/stats-base-dists-f-ctor

[@stdlib/stats/base/dists/f/entropy]: https://github.com/stdlib-js/stats-base-dists-f-entropy

[@stdlib/stats/base/dists/f/kurtosis]: https://github.com/stdlib-js/stats-base-dists-f-kurtosis

[@stdlib/stats/base/dists/f/mean]: https://github.com/stdlib-js/stats-base-dists-f-mean

[@stdlib/stats/base/dists/f/mode]: https://github.com/stdlib-js/stats-base-dists-f-mode

[@stdlib/stats/base/dists/f/skewness]: https://github.com/stdlib-js/stats-base-dists-f-skewness

[@stdlib/stats/base/dists/f/stdev]: https://github.com/stdlib-js/stats-base-dists-f-stdev

[@stdlib/stats/base/dists/f/variance]: https://github.com/stdlib-js/stats-base-dists-f-variance

[@stdlib/stats/base/dists/f/cdf]: https://github.com/stdlib-js/stats-base-dists-f-cdf

[@stdlib/stats/base/dists/f/pdf]: https://github.com/stdlib-js/stats-base-dists-f-pdf

[@stdlib/stats/base/dists/f/quantile]: https://github.com/stdlib-js/stats-base-dists-f-quantile

<!-- </toc-links> -->

</section>

<!-- /.links -->
