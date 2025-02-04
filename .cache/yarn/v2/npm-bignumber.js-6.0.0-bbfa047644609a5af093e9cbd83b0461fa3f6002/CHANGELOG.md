#### 6.0.0
* 26/01/2018
* #137 Implement `APLHABET` configuration option.
* Remove `ERRORS` configuration option.
* Remove `toDigits` method; extend `precision` method accordingly.
* Remove s`round` method; extend `decimalPlaces` method accordingly.
* Remove methods: `ceil`, `floor`, and `truncated`.
* Remove method aliases: `add`, `cmp`, `isInt`, `isNeg`, `trunc`, `mul`, `neg` and `sub`.
* Rename methods: `shift` to `shiftedBy`, `another` to `clone`, `toPower` to `exponentiatedBy`, and `equals` to `isEqualTo`.
* Rename methods: add `is` prefix to `greaterThan`, `greaterThanOrEqualTo`, `lessThan` and `lessThanOrEqualTo`.
* Add methods: `multipliedBy`, `isBigNumber`, `isPositive`, `integerValue`, `maximum` and `minimum`.
* Refactor test suite.
* Add *CHANGELOG.md*.
* Rewrite *bignumber.d.ts*.
* Redo API image.

#### 5.0.0
* 27/11/2017
* #81 Don't throw on constructor call without `new`.

#### 4.1.0
* 26/09/2017
* Remove node 0.6 from *.travis.yml*.
* Add *bignumber.mjs*.

#### 4.0.4
* 03/09/2017
* Add missing aliases to *bignumber.d.ts*.

#### 4.0.3
* 30/08/2017
* Add types: *bignumber.d.ts*.

#### 4.0.2
* 03/05/2017
* #120 Workaround Safari/Webkit bug.

#### 4.0.1
* 05/04/2017
* #121 BigNumber.default to BigNumber['default'].

#### 4.0.0
* 09/01/2017
* Replace BigNumber.isBigNumber method with isBigNumber prototype property.

#### 3.1.2
* 08/01/2017
* Minor documentation edit.

#### 3.1.1
* 08/01/2017
* Uncomment `isBigNumber` tests.
* Ignore dot files.

#### 3.1.0
* 08/01/2017
* Add `isBigNumber` method.

#### 3.0.2
* 08/01/2017
* Bugfix: Possible incorrect value of `ERRORS` after a `BigNumber.another` call (due to `parseNumeric` declaration in outer scope).

#### 3.0.1
* 23/11/2016
* Apply fix for old ipads with `%` issue, see #57 and #102.
* Correct error message.

#### 3.0.0
* 09/11/2016
* Remove `require('crypto')` - leave it to the user.
* Add `BigNumber.set` as `BigNumber.config` alias.
* Default `POW_PRECISION` to `0`.

#### 2.4.0
* 14/07/2016
* #97 Add exports to support ES6 imports.

#### 2.3.0
* 07/03/2016
* #86 Add modulus parameter to `toPower`.

#### 2.2.0
* 03/03/2016
* #91 Permit larger JS integers.

#### 2.1.4
* 15/12/2015
* Correct UMD.

#### 2.1.3
* 13/12/2015
* Refactor re global object and crypto availability when bundling.

#### 2.1.2
* 10/12/2015
* Bugfix: `window.crypto` not assigned to `crypto`.

#### 2.1.1
* 09/12/2015
* Prevent code bundler from adding `crypto` shim.

#### 2.1.0
* 26/10/2015
* For `valueOf` and `toJSON`, include the minus sign with negative zero.

#### 2.0.8
* 2/10/2015
* Internal round function bugfix.

#### 2.0.6
* 31/03/2015
* Add bower.json. Tweak division after in-depth review.

#### 2.0.5
* 25/03/2015
* Amend README. Remove bitcoin address.

#### 2.0.4
* 25/03/2015
* Critical bugfix #58: division.

#### 2.0.3
* 18/02/2015
* Amend README. Add source map.

#### 2.0.2
* 18/02/2015
* Correct links.

#### 2.0.1
* 18/02/2015
* Add `max`, `min`, `precision`, `random`, `shiftedBy`, `toDigits` and `truncated` methods.
* Add the short-forms: `add`, `mul`, `sd`, `sub` and `trunc`.
* Add an `another` method to enable multiple independent constructors to be created.
* Add support for the base 2, 8 and 16 prefixes `0b`, `0o` and `0x`.
* Enable a rounding mode to be specified as a second parameter to `toExponential`, `toFixed`, `toFormat` and `toPrecision`.
* Add a `CRYPTO` configuration property so cryptographically-secure pseudo-random number generation can be specified.
* Add a `MODULO_MODE` configuration property to enable the rounding mode used by the `modulo` operation to be specified.
* Add a `POW_PRECISION` configuration property to enable the number of significant digits calculated by the power operation to be limited.
* Improve code quality.
* Improve documentation.

#### 2.0.0
* 29/12/2014
* Add `dividedToIntegerBy`, `isInteger` and `toFormat` methods.
* Remove the following short-forms: `isF`, `isZ`, `toE`, `toF`, `toFr`, `toN`, `toP`, `toS`.
* Store a BigNumber's coefficient in base 1e14, rather than base 10.
* Add fast path for integers to BigNumber constructor.
* Incorporate the library into the online documentation.

#### 1.5.0
* 13/11/2014
* Add `toJSON` and `decimalPlaces` methods.

#### 1.4.1
* 08/06/2014
* Amend README.

#### 1.4.0
* 08/05/2014
* Add `toNumber`.

#### 1.3.0
* 08/11/2013
* Ensure correct rounding of `sqrt` in all, rather than almost all, cases.
* Maximum radix to 64.

#### 1.2.1
* 17/10/2013
* Sign of zero when x < 0 and x + (-x) = 0.

#### 1.2.0
* 19/9/2013
* Throw Error objects for stack.

#### 1.1.1
* 22/8/2013
* Show original value in constructor error message.

#### 1.1.0
* 1/8/2013
* Allow numbers with trailing radix point.

#### 1.0.1
* Bugfix: error messages with incorrect method name

#### 1.0.0
* 8/11/2012
* Initial release
