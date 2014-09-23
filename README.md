## cli

cli for imagerjs

## Requirements

* node 0.11.x with `--harmony` flag
* create `nodeh` as an alias to `node --harmony`

```sh
$ cat ~/bin/nodeh
#!/bin/bash
node --harmony "$@"
```

## Installation

```sh
$ npm install imager-cli -g
```

## Usage

```sh
$ imager -h

  Usage: imager [options] [command]

  Commands:

    upload <path>
       Upload the image at <path> to s3

    setup <key> <secret> <container> <region> <provider>
       Stores the imager config in ~/.imager.json


  Options:

    -h, --help                   output usage information
    -V, --version                output the version number
    -k, --key <key>              Key
    -s, --secret <secret>        Secret
    -c, --container <container>  Container
    -r, --region <region>        Region
    -p, --provider <provider>    Provider (one of amazon, rackspace)

```

## License

MIT
