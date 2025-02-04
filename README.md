# ZE CLI

A command line interface for ZE cryptocurrency mining.

## 📦 Install

To install the CLI, use [cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html):

```sh
cargo install ze-cli
```


### Dependencies
If you run into issues during installation, please install the following dependencies for your operating system and try again:

#### Linux
```
sudo apt-get install openssl pkg-config libssl-dev
```

#### MacOS
```
brew install openssl pkg-config

# If you encounter issues with OpenSSL, you might need to set the following environment variables:
export PATH="/usr/local/opt/openssl/bin:$PATH"
export LDFLAGS="-L/usr/local/opt/openssl/lib"
export CPPFLAGS="-I/usr/local/opt/openssl/include"
```

#### Windows
```
choco install openssl pkgconfiglite
```

## ⛏️ Mine

To start mining, load your keypair with some SOL and $ZeMine, and then use the `mine` command:

```sh
ze mine
```

## ❓ Help

Add the `-h` flag on any command to pull up a help menu with documentation:

```sh
ze -h
```

For support, please join the Telegram and ask your question with the #Help tag.
