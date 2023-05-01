Put a short description of the package here that helps potential users
know whether this package might be useful for them.

## Features

You can trade cryptos on most popular dex at Ethereum and their subnets using this package, the 30 or 80 lines of code you needed before are now reduced to just a few.

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
