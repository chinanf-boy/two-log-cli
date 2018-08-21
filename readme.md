# two-log-cli [![Build Status](https://travis-ci.org/chinanf-boy/two-log-cli.svg?branch=master)](https://travis-ci.org/chinanf-boy/two-log-cli) [![codecov](https://codecov.io/gh/chinanf-boy/two-log-cli/badge.svg?branch=master)](https://codecov.io/gh/chinanf-boy/two-log-cli?branch=master)

> switch `ora` and `winston` , if `debug == true` log => `winston`, else log => `ora`

## DEMO

```
npm i -g two-log-cli
```

<p>
<img src="./imgs/demo1.gif" width="40%">
<img src="./imgs/demo2.gif" width="40%">
</p>

## CLI

> just Demo

```
$ two-log --help

	Usage
	  $ two-log -D

	Options
	  -D  Debug [Default: false]

	Examples
	  $ two-log
	  ora show
	  $ two-log -D
	  winston show
```

## module

- [two-log](https://github.com/chinanf-boy/two-log)

## License

MIT © [chinanf-boy](http://llever.com)
