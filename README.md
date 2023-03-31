# Hardhat + Foundry Template

```bash
git init
git pull https://github.com/Hareem-Saad/Hardhat-With-Foundry-Template.git
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

2- ```npm init ```

3- ```npm install --save-dev hardhat ```

4- ```npx hardhat ```

5- ```npm install --save-dev "hardhat@^2.13.0" "@nomicfoundation/hardhat-toolbox@^2.0.0"```

6- ```npm install --save-dev @openzeppelin/hardhat-upgrades ```

7- ```npm install --save-dev @nomiclabs/hardhat-ethers ethers ```

8- ```npm i --save-dev dotenv @openzeppelin/contracts-upgradeable @openzeppelin/contracts ```

9- ```npm install --save-dev @nomicfoundation/hardhat-foundry ```

10- Add this in you hardhat config: import "@nomicfoundation/hardhat-foundry";

11- Commit or Stash all the code, next step require clean working tree

12- Install forge-std```forge install foundry-rs/forge-std```

13- Run ```npx hardhat init-foundry```

# What is has

- Hardhat

- Foundry

- @openzeppelin/hardhat-upgrades

- @nomiclabs/hardhat-ethers ethers

- dotenv

- @openzeppelin/contracts-upgradeable

- @openzeppelin/contracts

# NOTE: Important
folder lib has forge-std which is a git repository, cloning this may cause issues in pushing code to other repos
first run ```forge test``` it will install forge-std
then delete .git folder from this repo and lib/forge-std and push it again
