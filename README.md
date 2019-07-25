# Wavelet Faucet

A react component to tap into the Wavelet Faucet Testnet and add PERLs to a wallet.

## Usage

```
<WaveletFaucet 
    address="hex-encoded"
    onSuccess={onSuccessHandler}
    onError={onErrorHandler}
    defaultButton={custom element of ref}
    faucetUrl="alternative-faucet-url" 
/>
```

## Development

### `npm start`

Runs the component in the watch mode.

### `npm run build`

Builds the comopnent for production to the `build` folder.<br>