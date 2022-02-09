# Tonswap

## This project is TRC20 + AMM built in, including Liquidity Pool and fees
This project tries to combine a [TRC20](https://github.com/cod1ng-studio/TRC20) based and an AMM [uniswap](https://github.com/Uniswap/v2-core) 

### Compile Contract and RUN Fift Tests
In order to run this project you need a this binaris **fift** **func** and **lite-client** , you can install from [source](https://ton.org/docs/#/howto/getting-started) or use [tncli](https://github.com/disintar/tncli) or just run `pip install tncli` 

after you installing **fift** and **func** copy or symlink the binaries to root folder `ln -s ~/src/func ./func` and `ln -s ~/src/fift ./fift`

### Run Tests
`npm run test-dex`  for non npm users just run `./scripts/test-dex.sh`


### Roadmap

- [X] - Basic Bot with TRC20 interaction
- [X] - AMM with 0.03% Fees 
- [X] - Add Liquidity + Fift Tests
- [X] - Remove Liquidity + Fift Tests
- [X] - Swap TON -> Token and Token -> TON Tests (based on Uniswap)
- [X] - Swap Tests in Fift
- [X] - Masterchef with rewards 
- [ ] - Masterchef Rewards with Tests 
- [ ] - Send receipt based on TRC20
- [ ] - Deploy Contract to mainnet
- [ ] - Connect Bot to mainnet
- [ ] - Add Masterchef functionality with auto stake and auto withdraw inside the contract


