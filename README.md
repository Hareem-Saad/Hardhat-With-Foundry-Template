# Hardhat + Foundry Template

```bash
git init
```

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```

# How it was created
1- Create an empty project
2- ```shell npm init ```
3- ```shell npm install --save-dev hardhat ```
4- ```shell npx hardhat ```
5- ```shell npm install --save-dev "hardhat@^2.13.0" "@nomicfoundation/hardhat-toolbox@^2.0.0"```
6- ```shell npm install --save-dev @openzeppelin/hardhat-upgrades ```
7- ```shell npm install --save-dev @nomiclabs/hardhat-ethers ethers ```
8- ```shell npm i --save-dev dotenv @openzeppelin/contracts-upgradeable @openzeppelin/contracts ```
9- ```shell npm install --save-dev @nomicfoundation/hardhat-foundry ```
10- Add this in you hardhat config: import "@nomicfoundation/hardhat-foundry";
11- Install forge-std```forge forge install foundry-rs/forge-std```
