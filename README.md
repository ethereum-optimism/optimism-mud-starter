<div align="center">
  <div align="center">
  <a href="https://v2.mud.dev/"><img width="205" alt="mud logo" src="https://github.com/ethereum-optimism/optimism-mud-starter/assets/35039927/598580a6-0da5-40bc-8b5b-8a3f4a45a29a">
  </a>
  <br />
  <br />
  ✦
  <br />
  <br />
  <a href="https://optimism.io"><img alt="Optimism" src="https://raw.githubusercontent.com/ethereum-optimism/brand-kit/main/assets/svg/OPTIMISM-R.svg" width=320></a>
  <br />
  <h2><a href="https://optimism.io">Optimism Mud</a> starterkit.</h2>
  <br />
  </div>
</div>

This is a [Optimism](https://github.com/ethereum-optimism) + [MUD](https://github.com/latticexyz/mud)

## Who is this for?

MUD is a full-stack Dapp development framework. Think of it as the Ruby-on-Rails or NEXT.js of Dapp development.

It comes with the following features

- Automatic indexer generation with [MUD storage](https://v2.mud.dev/mode)
- Automatic frontend SDK generation to the [mud store](https://v2.mud.dev/store/reading-and-writing)
- Uniquely [gas efficient storage](https://v2.mud.dev/store/gas-efficiency)
- An amazing [cli](https://v2.mud.dev/cli) with great code generation tools

This starter is a great choice for any of the following groups:

- Hackers hacking on [Optimism](https://www.optimism.io/)
- Hackers interested in trying out an opinionated full stack framework

MUD2 is in alpha. Looking for a more traditional starterkit? Check out [Optimism Starter](https://github.com/ethereum-optimism/optimism-starter)

## Why MUD?

MUD takes care of all the plumbing of building blockchain-based applications so you can focus on your application logic.

TODO link a video here

## Getting Started

### Install Node 18

[See here](https://nodejs.org/en/download/).

### Install Foundry

You will need to install [Foundry](https://book.getfoundry.sh/getting-started/installation) to build your smart contracts.

1. Run the following command:

   ```sh
   curl -L https://foundry.paradigm.xyz | bash
   ```

1. Source your environment as requested by Foundry.

1. Run `foundryup`.

</details>

### Install pnpm

Pnpm is the package manager MUD uses. It's usage is very similar to NPM but speed is much faster

```bash
npm install pnpm --global
```

## Start the application

<img width="450" alt="starter-app-screenshot" src="https://user-images.githubusercontent.com/389705/225778318-4e6fb8c0-c5d7-4aea-9fc2-2efd17ca435c.png">

1. Clone/fork the optimism-mud-starter repo

   ```sh
   git clone https://github.com/ethereum-optimism/optimism-mud-starter.git
   ```

2. Install the necessary node packages:

   ```sh
   cd optimism-mud-starter
   pnpm install
   ```

3. Initialize the mud project

   ```sh
   pnpm initialize
   ```

   If you get errors during this step, you might need to [update your Foundry to the latest version](#install-foundry).

4. Start dev server

```sh
pnpm dev
```

5. Open [localhost:3000](http://localhost:3000) in your browser.

See below for general usage instructions or [FAQ](./FAQ.md) for answers to general questions such as:

- [Where to get goerli eth]().
- [How to deploy a public version of your app](./FAQ.md#how-do-i-deploy-this).

## Check out the MUD documentation

MUD is in Alpha so make sure to check out the [official MUD documentation](https://v2.mud.dev/) for latest usage instructions.

## Join the MUD discord

MUD has a vibrant community ready to help. [Join the discord](https://discord.com/invite/CzXAgtFqgq) to share your MUD project or ask any questions.

## Set up environment

### Get an Etherscan key

1. Register for [Etherscan on Optimism](https://explorer.optimism.io/register).
   This account is different from your normal Etherscan account.

2. Go to [the API keys page](https://explorer.optimism.io/myapikey) and click **Add** to create a new API key.

3. You can now [add the etherscan key to your foundry.toml](https://book.getfoundry.sh/reference/config/etherscan?highlight=etherscan#etherscan)

## Alternatives

Looking to use burner wallets? Prefer hardhat? Prefer NEXT.js? Check out these amazing alternatives:

- [optimism starter](https://github.com/ethereum-optimism/optimism-starter) - A more traditional wagmi/viem based starterkit
- [create mud](https://v2.mud.dev/cli#create) - This starterkit uses the react template. MUD offers a vanillajs version too
- [create wagmi cli](https://wagmi.sh/cli/create-wagmi) - A flexible cli with many templates (this starterkit was started from vite-react-cli-foundry)
- [scaffold-eth](https://github.com/scaffold-eth/se-2) - The new 2nd version of a popular NEXT.js based starter including hardhat, burner wallets, great documentation, and an active telegram for support

## Learn more

- [MUD Documentation](https://v2.mud.dev/) – learn about wagmi Hooks and API.
- [Foundry Documentation](https://book.getfoundry.sh/) – learn more about the Foundry stack (Anvil, Forge, etc).
- [Vite Documentation](https://vitejs.dev/) – learn about Vite features and API.
