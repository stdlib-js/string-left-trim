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

# ltrim

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Trim whitespace characters from the beginning of a string.



<section class="usage">

## Usage

```javascript
import ltrim from 'https://cdn.jsdelivr.net/gh/stdlib-js/string-left-trim@esm/index.mjs';
```

#### ltrim( str )

Trims whitespace from the beginning of a string.

```javascript
var out = ltrim( ' \r\n\t  Beep \t\t\n  ' );
// returns 'Beep \t\t\n  '
```

</section>

<!-- /.usage -->

<section class="notes">

## Notes

-   Following [Unicode 6.3.0][unicode] and later, "whitespace" is defined as the following characters:

    -   `\f`
    -   `\n`
    -   `\r`
    -   `\t`
    -   `\v`
    -   `\u0020`
    -   `\u00a0`
    -   `\u1680`
    -   `\u2000-\u200a`
    -   `\u2028`
    -   `\u2029`
    -   `\u202f`
    -   `\u205f`
    -   `\u3000`
    -   `\ufeff`

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import ltrim from 'https://cdn.jsdelivr.net/gh/stdlib-js/string-left-trim@esm/index.mjs';

var str = ltrim( '   Whitespace   ' );
// returns 'Whitespace   '

str = ltrim( '\t\t\tTabs\t\t\t' );
// returns 'Tabs\t\t\t'

str = ltrim( '\n\n\nNew Lines\n\n\n' );
// returns 'New Lines\n\n\n'

</script>
</body>
</html>
```

</section>

<!-- /.examples -->



<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/string/trim`][@stdlib/string/trim]</span><span class="delimiter">: </span><span class="description">trim whitespace characters from the beginning and end of a string.</span>
-   <span class="package-name">[`@stdlib/string/right-trim`][@stdlib/string/right-trim]</span><span class="delimiter">: </span><span class="description">trim whitespace characters from the end of a string.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/string-left-trim.svg
[npm-url]: https://npmjs.org/package/@stdlib/string-left-trim

[test-image]: https://github.com/stdlib-js/string-left-trim/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/string-left-trim/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/string-left-trim/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/string-left-trim?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/string-left-trim.svg
[dependencies-url]: https://david-dm.org/stdlib-js/string-left-trim/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/string-left-trim/tree/deno
[umd-url]: https://github.com/stdlib-js/string-left-trim/tree/umd
[esm-url]: https://github.com/stdlib-js/string-left-trim/tree/esm
[branches-url]: https://github.com/stdlib-js/string-left-trim/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/string-left-trim/main/LICENSE

[standard-streams]: https://en.wikipedia.org/wiki/Standard_streams

[unicode]: https://en.wikipedia.org/wiki/Unicode

[mdn-regexp]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions

<!-- <related-links> -->

[@stdlib/string/trim]: https://github.com/stdlib-js/string-trim/tree/esm

[@stdlib/string/right-trim]: https://github.com/stdlib-js/string-right-trim/tree/esm

<!-- </related-links> -->

</section>

<!-- /.links -->
