# The Noir Programming Language

Noir is a Domain Specific Language for SNARK proving systems. It has been designed to use any ACIR compatible proving system.

**This implementation is in early development. It has not been reviewed or audited. It is not suitable to be used in production. Expect bugs!**

## Quick Start

Read the installation section [here](https://noir-lang.github.io/book/getting_started/nargo/installation.html).

Once you have read through the documentation, you can also run the examples located in the `examples` folder.

- [Official Resources](#official-resources)
- [Talks & Workshops](#talks--workshops)
- [Get Coding](#get-coding)
  - [Dev Tools](#dev-tools)
  - [Boilerplates](#boilerplates)
  - [Libraries](#libraries)
- [Projects](#projects)
  - [Authentication](#authentication)
  - [Education](#education)
  - [Gaming](#gaming)
  - [Governance](#governance)
- [Contribute](#contribute)

---

## Official Resources

- [Docs](https://noir-lang.github.io/book)
- [GitHub](https://github.com/noir-lang/noir)

## Talks & Workshops

- [20m] [Private Value Transfer in 10 Lines](https://www.youtube.com/watch?v=wYqqXas8_O4)
- [10m] [Writing Circuits with Noir](https://www.youtube.com/watch?v=I5M8LhOECpM&t=2879s)
- [2h] [ZK HACK III - Introduction to Noir](https://www.youtube.com/watch?v=5CziMfChveY)
- [1.5h] [Sudoku in Noir](https://drive.google.com/file/d/1D4XCdiIZVjUW1JHDoMW3pG-15mgjMm9E/)

## Get Coding

### Dev Tools

- [VSCode Extension](https://marketplace.visualstudio.com/items?itemName=noir-lang.noir-programming-language-syntax-highlighter) - Syntax highlighter
- [Vim Plugin](https://github.com/Louis-Amas/noir-vim-support) - Syntax highlighter
- [hardhat-noir](https://www.npmjs.com/package/hardhat-noir) - Hardhat Plugin

### Boilerplates

- [nplate](https://github.com/whitenois3/nplate) - Minimalist template
- [hello-noir](https://github.com/socathie/hello-noir) + [hello-noir-ui](https://github.com/socathie/hello-noir-ui/) - React template
- [noir-web-starter-next](https://github.com/noir-lang/noir-web-starter-next) - Next.js template

### Libraries

- [Standard Library](https://github.com/noir-lang/noir/tree/master/noir_stdlib)

## Projects

A curated list of projects powered by Noir.

### Authentication

- Anonymous proof of token ownership on Aztec (for token-gated access)
  - [Sequi](https://github.com/sequi-xyz)
  - [Cyclone](https://github.com/TalDerei/cyclone)

### Education

- [Mastermind](https://github.com/vezenovm/mastermind-noir) - Mastermind in Noir
- [Crypdoku](https://github.com/guipublic/crypdoku) - Sudoku in Noir
- [Basic Mul](https://github.com/vezenovm/basic_mul_noir_example) - Demonstrate Noir interactions in TypeScript
- [Private Value Tranfer](https://github.com/vezenovm/simple_shield) - Example implementation of Tornado-like private asset transfer using Merkle proofs

### Gaming

- [BattleZips](https://github.com/BattleZips/BattleZips-Noir) - ZK Battleship 
- [zkShips](https://github.com/snjax/zkships) - ZK Battleship (ETHBogota hackathon 1st place)

# ZKDocs
ZKDocs provides comprehensive, detailed, and interactive documentation on zero-knowledge proof systems and related primitives.

Checkout [zkdocs](zkdocs.com)

### Detailed
We describe each protocol in great detail, including all necessary setup, sanity-checks, auxiliary algorithms, further references, and potential security pitfalls with their associated severity.


### Interactive

The protocol descriptions are interactive, letting you modify variable names. This allows you to match the variable names in ZKdocs' specification to the variable names in your code, making it easier to find bugs and missing assertions.

![demo](https://user-images.githubusercontent.com/76808956/212434601-7c1100c6-7de6-42c7-83cc-28a6ab6841a7.gif)

Interactivity features:
 - Click on a variable to highlight it across the document.
 - Type or paste with a variable highlighted to edit its name. Press `Enter` or `Escape` to stop editing.
 - Press the `Reset variables names` button to reset the names of all variables on the current page (variable names are independent across different pages)

----
