
# Secure slowloris

  Slow loris attack testing tool with multiple socks proxying.

  ![](http://25.media.tumblr.com/tumblr_lzvsw7qrH81r94sbdo1_500.gif)

## Installation

```
$ npm install -g visionmedia/slowloris
```

## Config

Setup config.json - it defines an a json file containing a root json array which can take multiple socks5 configuration objects.
Each configurable object is of the form

```
{
  "host": "<socks proxy string>",
  "port": <socks port int>,
  "username": "<socks auth string (optional)>",
  "password": "<socks passwrord string (optional)>"
}
```


## Usage

```

  Usage: slowloris [options] <url>

  Options:

    -h, --help             output usage information
    -V, --version          output the version number
    -c, --connections <n>  number of connections to open [5000]

```

# License

  MIT
