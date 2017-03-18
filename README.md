# URL2Text
Command line utility for polling a URL and writing the contents to a file

## Setup
Install with `npm install --global url2text`.

## Use
See the most recent help by running `url2text --help`

```
url2text 0.1.0 - Command line utility for polling a URL and writing the contents to a file

USAGE

  url2text <url>

ARGUMENTS

  <url>      URL to pull content from      required

OPTIONS

  --location <location>      Write URL contents to <location>      optional      default: "url-to-text.txt"
  --interval <interval>      Refresh interval in ms                optional      default: 5000

GLOBAL OPTIONS

  -h, --help         Display help
  -V, --version      Display version
  --no-color         Disable colors
  --quiet            Quiet mode - only displays warn and error messages
  -v, --verbose      Verbose mode - will also output debug messages
```
