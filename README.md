# Wavelet Faucet

A react component to tap into the Wavelet Faucet Testnet and add PERLs to a wallet.

## Usage

```
import WaveletFaucet, {darkTheme, defaultTheme} from 'wavelet-faucet';
...

<WaveletFaucet 
    address="hex-encoded"
    onSuccess={onSuccessHandler}
    onError={onErrorHandler}
    trigger="#cssSelector"
    faucetUrl="alternative-faucet-url"
    theme={alternativeTheme}
/>
```
The component uses style-components with a default darkTheme. In order to customize the look'n'feel you can either pass in your own theme or simply target class names.

Props:
- address - hex-encoded address of the wallet to fill in the input;
- onSuccess - function to be called on success. Defaults to alert();
- onError - function to be called whenver there's an error. Defaults to alert();
- trigger - if set it will use the target element to open the modal. Leave empty to create a floating button; 
- faucetUrl - url to call to get PERLs. Defaults to https://faucet.perlin.net/
- theme - theme object to override styling. Defaults to darkTeme



## Development

### `npm start or yarn start`

Runs the component in the watch mode.

### `npm run build or yarn build`

Builds the comopnent for production to the `build` folder.<br>