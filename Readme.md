# Install Dependencies
`npm i`

[Download Ghanache](https://trufflesuite.com/ganache/)


# Use Sample

`truffle unbox`

Or do it manually

# Init Repo
`truffle init`

# Build Smart Contract .sol

`truffle compile`

# Setup Dev Env using Ganache


# Update Config

Update `truffle-config.js` with development network details

# Migrate compiled contract

`truffle migrate`

if after migrate no new migrations appeared - `truffle migrate --reset`

# Tips
## Reset project

`rm -r build/`

`rm .openzeppelin/project.json`

`truffle compile`
