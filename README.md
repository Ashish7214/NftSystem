# NFT Management System

This is a simple NFT (Non-Fungible Token) management system implemented in JavaScript.

## Assesment Required
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [License](#license)

## Introduction

This project is a basic NFT management system that allows you to create and store NFTs with minimal metadata. It demonstrates how to use JavaScript functions to create NFT objects and store them in an array.

## Features

- Create NFTs: The `mintNFT` function allows you to create NFTs by providing a `tokenID`.
- List NFTs: The `listNFTs` function prints the metadata of all the created NFTs to the console.
- Get Total Supply: The `getTotalSupply` function returns the total number of NFTs created.


## Usage

Here's how you can use the NFT management system:

```javascript
// Call your functions below this line
mintNFT(123456);
mintNFT(789012);
mintNFT(345678);

listNFTs();

console.log("Total NFTs: " + getTotalSupply());

```


## Author

**Ashish Kumar**

- GitHub: [github.com/Ashish7214](https://github.com/Ashish7214)
- Email: 22bcs80055@cuchd.in

## License
This project is licensed under the [MIT License](LICENSE).
