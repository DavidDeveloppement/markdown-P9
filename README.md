# Airbnb JavaScript Style Guide() {

*A mostly reasonable approach to JavaScript*

> **Note**: this guide assumes you are using [Babel](https://babeljs.io), and requires that you use [babel-preset-airbnb](https://npmjs.com/babel-preset-airbnb) or the equivalent. It also assumes you are installing shims/polyfills in your app, with [airbnb-browser-shims](https://npmjs.com/airbnb-browser-shims) or the equivalent.

[![Downloads](https://img.shields.io/npm/dm/eslint-config-airbnb.svg)](https://www.npmjs.com/package/eslint-config-airbnb)
[![Downloads](https://img.shields.io/npm/dm/eslint-config-airbnb-base.svg)](https://www.npmjs.com/package/eslint-config-airbnb-base)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/airbnb/javascript?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

This guide is available in other languages too. See [Translation](#translation)

Other Style Guides

  - [ES5 (Deprecated)](https://github.com/airbnb/javascript/tree/es5-deprecated/es5)
  - [React](react/)
  - [CSS-in-JavaScript](css-in-javascript/)
  - [CSS & Sass](https://github.com/airbnb/css)
  - [Ruby](https://github.com/airbnb/ruby)

## Table of Contents

    1. [Types](#types)
    2. [References](#references)
    3. [Objects](#objects)
    4. [Arrays](#arrays)
    5. [Destructuring](#destructuring)
    6. [Strings](#strings)
    7. [Functions](#functions)
    8. [Arrow Functions](#arrow-functions)
    9. [Classes & Constructors](#classes--constructors)
    10. [Modules](#modules)
    11. [Iterators and Generators](#iterators-and-generators)
    12. [Properties](#properties)
    13. [Variables](#variables)
    14. [Hoisting](#hoisting)
    15. [Comparison Operators & Equality](#comparison-operators--equality)
    16. [Blocks](#blocks)
    17. [Control Statements](#control-statements)
    18. [Comments](#comments)
    19. [Whitespace](#whitespace)
    20. [Commas](#commas)
    21. [Semicolons](#semicolons)
    22. [Type Casting & Coercion](#type-casting--coercion)
    23. [Naming Conventions](#naming-conventions)
    24. [Accessors](#accessors)
    25. [Events](#events)
    26. [jQuery](#jquery)
    27. [ECMAScript 5 Compatibility](#ecmascript-5-compatibility)
    28. [ECMAScript 6+ (ES 2015+) Styles](#ecmascript-6-es-2015-styles)
    29. [Standard Library](#standard-library)
    30. [Testing](#testing)
    31. [Performance](#performance)
    32. [Resources](#resources)
    33. [In the Wild](#in-the-wild)
    34. [Translation](#translation)
    35. [The JavaScript Style Guide Guide](#the-javascript-style-guide-guide)
    36. [Chat With Us About JavaScript](#chat-with-us-about-javascript)
    37. [Contributors](#contributors)
    38. [License](#license)
    39. [Amendments](#amendments)