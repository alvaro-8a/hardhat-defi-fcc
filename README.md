# DeFi Smart Contract Hardhat Project

<div id="top"></div>

[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- ABOUT THE PROJECT -->

## About The Project

Check the Smart Contract deployed on Rinkeby Network [here](https://rinkeby.etherscan.io/address/0xd9ac6213E0191b597883CFe79f377cD6637f34bE#code)

All the code was developed for learning purposes and is from [Learn Blockchain, Solidity, and Full Stack Web3 Development with JavaScript – 32-Hour Course](https://www.youtube.com/watch?v=gyMwXuJrbJQ&lis) by freeCodeCamp.org and Patrick Collins

The project represents a defi project that interacts with the aave protocol, it implements some aave interfaces, like the LendingPool Interface.

All the projects works on a local network but "simulating" the ethereum mainnet, this is possible with the forking system that implements hardhat

You will be able to simulate the programatically deposit of collateral on aave (automatically converting the ETH in WETH to be able to transfer it to the aave protocol)

Then you will be borrowing another asset, in this example the asset used is DAI

And finally you will repay the DAI borrowed and recover the money you deposited (Not all because the protocol takes some interests)

**Note:** When you repay the DAI, you still owe some DAI to the protocol because of the accrued interests. You would have to change some ETH for DAI in Uniswap to totally pay the debt

This project demonstrates an advanced Hardhat use case, integrating other tools commonly used alongside Hardhat in the ecosystem.

// TradeOffs of forking a network

Pros: Quick, easy, resemble what's on mainnet
Cons: We need an API, some contracts are complex to work with

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

-   [Node.js](https://nodejs.org/)
-   [Solidity](https://docs.soliditylang.org/)
-   [Hardhat](https://hardhat.org/)
-   [AAVE protocol](https://docs.aave.com/developers/v/2.0/the-core-protocol/protocol-overview)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Make sure you have already installed Node.js in your device. In case you have, upgrade npm to the latest version

-   npm
    ```sh
    npm install npm@latest -g
    ```

### Installation

1. Clone the repo
    ```sh
    git clone https://github.com/alvaro-8a/hardhat-erc20-fcc.git
    ```
2. Install YARN packages
    ```sh
    yarn
    ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

You can use this code as a learning case on how to programatically interact with the aave protocol and how to develop a defi application (depositing, borrowing and repaying to aave) 

You can also implement the Uniswap code to automatically fully repay the DAI debt

**Note: This project is a demo and I don't recommend using it without changes, there are many things that can be improved so take in consideration before using it.**

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

-   [✔️] Deposit collateral: ETH / WETH
-   [✔️] Borrow another asset: DAI
-   [✔️] Repay the DAI
-   [	] Uniswap code to fully pay the debt

See the [open issues](https://github.com/alvaro-8a/hardhat-erc20-fcc/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion or an improvement that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Your Name - [@alvaro*8a*](https://twitter.com/alvaro_8a_) - alvaroblanco8a@gmail.com

Project Link: [https://github.com/alvaro-8a/hardhat-erc20-fcc](https://github.com/alvaro-8a/hardhat-erc20-fcc)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

-   [Learn Blockchain, Solidity, and Full Stack Web3 Development with JavaScript – 32-Hour Course](https://www.youtube.com/watch?v=gyMwXuJrbJQ&lis)
-   [Patrick Collins](https://www.youtube.com/c/PatrickCollins)
-   [FreeCodeCamp.org](https://www.youtube.com/c/Freecodecamp)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/alvaro-8a/hardhat-erc20-fcc.svg?style=for-the-badge
[contributors-url]: https://github.com/alvaro-8a/hardhat-erc20-fcc/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/alvaro-8a/hardhat-erc20-fcc.svg?style=for-the-badge
[forks-url]: https://github.com/alvaro-8a/hardhat-erc20-fcc/network/members
[stars-shield]: https://img.shields.io/github/stars/alvaro-8a/hardhat-erc20-fcc.svg?style=for-the-badge
[stars-url]: https://github.com/alvaro-8a/hardhat-erc20-fcc/stargazers
[issues-shield]: https://img.shields.io/github/issues/alvaro-8a/hardhat-erc20-fcc.svg?style=for-the-badge
[issues-url]: https://github.com/alvaro-8a/hardhat-erc20-fcc/issues
[license-shield]: https://img.shields.io/github/license/alvaro-8a/hardhat-erc20-fcc.svg?style=for-the-badge
[license-url]: https://github.com/alvaro-8a/hardhat-erc20-fcc/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/alvaro-blanco-ochoa-9b14561a9
[product-screenshot]: images/screenshot.png