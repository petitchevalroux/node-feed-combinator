# node-feed-aggregator
Duplex stream and cli command which aggregate rss/atom feeds

## About

### Command
Command takes a [configuration file](https://github.com/petitchevalroux/node-feed-aggregator/blob/master/config/sample.json)
with multiple feeds and output an aggregated feed sorted by decreasing publication date.

### Package
Package exposes a stream taking feed's urls as input and output all items sorted by decreasing publication date.

## Command install
```
npm install -g "@petitchevalroux/node-feed-aggregator"
```

## Command update
```
npm update -g "@petitchevalroux/node-feed-aggregator"
```

## Command usage
```
Usage: node-feed-aggregator -c <config file> [-o <output file>] [-h]
        -c: (mandatory) path to configuration file
        -o: (optional) path to output file default is to output to stdout
        -h: (optional) display this help and exit
```

## Configuration file
See : [sample.json](https://github.com/petitchevalroux/node-feed-aggregator/blob/master/config/sample.json)

## Package install
```
npm install --save "@petitchevalroux/node-feed-aggregator"
```

## Package usage
See : [sample.js](https://github.com/petitchevalroux/node-feed-aggregator/blob/master/src/sample.js)
