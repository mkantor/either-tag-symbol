# either-tag-symbol

A symbol used to indicate that an object models the standard `Either` algebraic
data type.

This package is not meant to be used directly. Instead, depend on
[my `either` package](https://www.npmjs.com/package/@matt.kantor/either). This
symbol lives in a separate package to allow versioning the `either` API while
mitigating [dependency hell](https://en.wikipedia.org/wiki/Dependency_hell) in
consuming packages.
