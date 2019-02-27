# EthTracker

A simple react-native app built with Expo.


#### Mandatory
- [x] Input field for Ethereum address
- [x] Easy access to EthereumAccount screen
- [x] Display ETH and ERC20 balances
- [x] Display address operations with value and direction

#### Optional
- [x] Display operation date
- [x] Pull to refresh tokens and operations
- [x] QRCode reader to pre-fill input
- [x] Counter-values to balances and operations
- [ ] Sort tokens by their counter-values
- [ ] Coin distribution in Pie Chart
- [x] Fold and unfold lists
- [ ] Group the operations by day

#### Coffee
- [x] Display history of previous searches
- [x] Data persistence between sessions


## Development

This app depends on the Coinmarketcap api.
To run in development you will need to create a file named `.env.js` at the root that exports an object containing your API_KEY.

```
  const env = {
    API_KEY: <SECRET_API_KEY>
  }

  export default env
```