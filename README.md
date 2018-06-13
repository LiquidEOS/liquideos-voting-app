# sheos-vote

We created a standalone EOS voting application that signs your transactions locally with your private key and then executes the transaction on the blockchain. The reason for this is multi-fold:

1. The only EOS voting tool that is endorsed is a command line application which is difficult to install and use and will greatly limit access to voting.
2. Scatter, the most popular EOS wallet, did not receive an official endorsement from the community as a safe voting tool and many voters have reported having issues importing their accounts.
3. The alternative web voting interface relies on Scatter, and even though your private key never leaves your browser, we wanted to provide you an extra level of security through an application that runs outside the browser and the potential reach of toolbars, botnets and other bad actors.

Forked from LiquidEOS

## To Download

* **[sheos-vote-windows-1.0.0.zip](https://www.dropbox.com/s/lpntpv2su1snah4/sheos-vote_v1.0.0_OSX.zip?dl=1)**
* **[sheos-vote-macos-1.0.0.zip](https://www.dropbox.com/s/t7tre5prv8ux4zg/sheos-vote_v1.0.0_WIN.zip?dl=1)**

## To Use

```bash
# Clone this repository
git@github.com:
git clone https://github.com/sheos-org/sheos-voting-app.git
# Go into the repository
cd sheos-voting-app
# Install dependencies
npm install
# Run the app
npm start
```


## To Build

```bash
# Clone this repository
git clone https://github.com/sheos-org/sheos-voting-app.git
# Go into the repository
cd sheos-voting-app
# Install dependencies
npm install
# Create distribution
npm run dist
```

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
