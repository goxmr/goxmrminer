# go-xmr-miner

High performance Monero (XMR) Stratum protocol proxy in go.

Browser mining on any pool using javaScript library.

## Usage

### Download

```
wget https://github.com/goxmr/goxmrminer/archive/master.zip
unzip master.zip
cd goxmrminer-master
chmod +x goxmrminer-linux-amd64
```

### Configuration

Edit `conf.json` file

```
{
  "http_port": "8182",
  "https_port": "443",
  "tls_crt_file": "",
  "tls_key_file": "",
  "addr": "YOUR_MONERO_ADDRESS",
  "pool": "pool.supportxmr.com:3333",
  "pool_pass": "x",
  "stats_pass": "admin"
}
```

Find and replace `localhost:8182` to YOUR_SITE in `./static/miner/miner.min.js` and `./static/miner/cryptonight-asmjs.min.js`

### Run

```
./goxmrminer-linux-amd64
```

### Open in browser

```
http://yoursite.com:8182
```
## Live Demo

https://goxmrminer.com/demo.html

## Disclaimer

This project is not endorsed by or affiliated with coinhive.com in any way.
