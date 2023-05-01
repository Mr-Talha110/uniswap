## Uniswap 

This package contains all the features of the Uniswap Smart contract and supports its use on other exchanges and other networks. 

## Features

You can do swaps on the most popular dexs of Ethereum and their subnets using this package, the 30 or 80 lines of code you needed before are now reduced to just a few.

## Supported exchanges


- [Uniswap](https://app.uniswap.org/)

- [Pancakeswap](https://pancakeswap.finance)

- [Quickswap](https://quickswap.exchange)

## Supported functions 


- `swapExactETHForTokens`

- `swapExactTokensForETH`

- `swapExactTokensForTokens`

- `swapETHForExactTokens`

- `swapTokensForExactETH`

- `swapTokensForExactTokens`

## Getting started

Add the package to your pubspec.yaml file as shown below.
```dart

dependencies:

  uniswap: any

```


## Usage

Below you will see some examples of how to implement each function.

```dart
final swapExactETHForTokens = await Uniswap().swapExactETHForTokens();
```

## Additional information

Initially this package was created for personal use in order to avoid writing so much code rather perform swaps with just 5 to 10 lines.

You can check the code if you have doubts regarding security, any contribution or idea to improve is welcome!

Greetings and I hope you find it useful. ⚡
