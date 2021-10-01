
# Exercise 5: Erc20 Example

This is the exercise for ERC20 with ink!.

## Build

```sh
cargo +nightly contract build
```

## Test

```sh
cargo +nightly test
```

The test results should be:
![Test results Picture](https://github.com/IanGYan/exercise5-erc20-example/blob/main/test-result.jpeg)

## Deployment

Use [Canvas UI](https://paritytech.github.io/canvas-ui/#/) to deply the ERC20 contract and test.
Please refer to [Substrate Developer Hub](https://substrate.dev/substrate-contracts-workshop/#/0/deploy-contract?id=upload-contract-code-and-instantiate-a-contract-on-the-blockchain) for more details.

Here're some of the deployment pictures with Canvas UI.

1) Deployed
![Deployed](https://github.com/IanGYan/exercise5-erc20-example/blob/main/res/d1.jpg)

2) Instantiated
![Instantiated 1](https://github.com/IanGYan/exercise5-erc20-example/blob/main/res/d4.jpg)
![Instantiated 2](https://github.com/IanGYan/exercise5-erc20-example/blob/main/res/d2.jpg)

3) Approve(Alice -> Bob)
![Approve 1](https://github.com/IanGYan/exercise5-erc20-example/blob/main/res/d6.jpg)

4) Transfer(Alice -> Ferdie)
![Transfer](https://github.com/IanGYan/exercise5-erc20-example/blob/main/res/d7.jpg)

5) Transfer_from(Bob: Alice -> Charlie)
![Transfer_from 1](https://github.com/IanGYan/exercise5-erc20-example/blob/main/res/d8.jpg)
![Transfer_from 2](https://github.com/IanGYan/exercise5-erc20-example/blob/main/res/d9.jpg)

6) The results of calls
![results](https://github.com/IanGYan/exercise5-erc20-example/blob/main/res/dx.jpg)
