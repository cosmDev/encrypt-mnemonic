# encrypt-mnemonic

This library allows you to Encrypt and Decrypt in NodeJS your mnenomics

## Installation

Use the package manager [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) to install encrypt-mnemonic.

```bash
npm install @cosmdev/encrypt-mnemonic
```

## Usage

```js
import { encrypt, decrypt } from "@cosmdev/encrypt-mnemonic";

const mnemonic = "blush logic differ loud brother noble multiply child bring wheat start rain"
const pass = "secret1234"

const encMnemonic = encrypt(mnemonic, pass)
console.log('encrypted mnemonic', encMnemonic);

const decMnemonic = decrypt(encMnemonic, pass)
console.log('decrypted mnemonic', decMnemonic);

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0)