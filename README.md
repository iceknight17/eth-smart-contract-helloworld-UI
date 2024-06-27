# 🗃 Hello World Part 4 Tutorial Starter Files

This project contains the starter files for [Hello World Part 4 tutorial](https://docs.alchemy.com/alchemy/tutorials/hello-world-smart-contract/creating-a-full-stack-dapp), in which we teach you how to create a full stack dApp by connecting your Hello World smart contract to a React frontend using Metamask and Web3 tools.

- update node module /hello-world-part-four-tutorial/starter-files/node_modules/react-scripts/config/webpack.config.js

Add the following to the resolve object in the file as shown below:

...
fallback: { "http": require.resolve("stream-http"),
      "https": require.resolve("https-browserify"), "zlib": require.resolve("browserify-zlib")  },
...