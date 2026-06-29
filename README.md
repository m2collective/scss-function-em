# SCSS Function Em

A package for integrating the `px` to `em` conversion function.

![npm](https://img.shields.io/npm/v/@m2collective/scss-function-em?style=for-the-badge)

___

## Installation

You can install the package automatically using NPM:

```
npm i @m2collective/scss-function-em
```

## Usage

To use the package, import it into your project:

```scss
@use "@m2collective/scss-function-em" as *;

.demo {
    font-size: em(16px);
}

// Return

.demo {
    font-size: 1em;
}
```

## Changing the namespace

You can change the namespace during function import and use the function with a different namespace:

```scss
@use "@m2collective/scss-function-em" as function;
```

## Changing the variables

You can redefine the default values for the specified variables when importing the function:

```scss
@use "@m2collective/scss-function-em" as * with (
    $default: 16,
);
```

## License

The MIT License (MIT). Please see the [License file](LICENSE.txt) for more information.
