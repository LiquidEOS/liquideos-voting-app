# liquideos-vote

We created a standalone EOS voting application that signs your transactions locally with your private key and then executes the transaction on the blockchain. The reason for this is multi-fold:

1. The only EOS voting tool that is endorsed is a command line application which is difficult to install and use and will greatly limit access to voting.
2. Scatter, the most popular Web3 EOS wallet, has never been tested on production and isn’t fully trusted.
3. The web voting tool we built only works on http, and even though your private key never leaves your browser, we wanted an extra level of security.


## To Download

* **[liquideos-vote-windows-1.0.0.zip](https://storage.googleapis.com/liquideos/voting-app/builds/liquideos-vote-windows-1.0.0.zip)**
* **[liquideos-vote-macos-1.0.0.zip](https://storage.googleapis.com/liquideos/voting-app/builds/liquideos-vote-macos-1.0.0.zip)**

## To Use

```bash
# Clone this repository
git@github.com:
git clone https://github.com/bancorprotocol/liquideos-voting-app.git
# Go into the repository
cd liquideos-voting-app
# Install dependencies
npm install
# Run the app
npm start
```


## To Build

```bash
# Clone this repository
git clone https://github.com/bancorprotocol/liquideos-voting-app.git
# Go into the repository
cd liquideos-voting-app
# Install dependencies
npm install
# Create distribution
npm run dist
```

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
