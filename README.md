# Lightnovel Crawler

[![Python version](https://img.shields.io/pypi/pyversions/lightnovel-crawler.svg)](https://pypi.org/project/lightnovel-crawler)
[![PyPI version](https://img.shields.io/pypi/v/lightnovel-crawler.svg)](https://pypi.org/project/lightnovel-crawler)
[![PyPI - Format](https://img.shields.io/pypi/format/lightnovel-crawler.svg)](https://pypi.org/project/lightnovel-crawler)
[![PyPI - Status](https://img.shields.io/pypi/status/lightnovel-crawler.svg)](https://pypi.org/project/lightnovel-crawler)
[![SayThanks.io](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/dipu-bd)
<br>
[![GitHub contributors](https://img.shields.io/github/contributors/dipu-bd/lightnovel-crawler.svg)](https://github.com/dipu-bd/lightnovel-crawler)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/dipu-bd/lightnovel-crawler.svg)](https://github.com/dipu-bd/lightnovel-crawler/pulls)
[![GitHub issues](https://img.shields.io/github/issues/dipu-bd/lightnovel-crawler.svg)](https://github.com/dipu-bd/lightnovel-crawler/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/dipu-bd/lightnovel-crawler.svg)](https://github.com/dipu-bd/lightnovel-crawler/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+)
[![GitHub](https://img.shields.io/github/license/dipu-bd/lightnovel-crawler.svg)](https://github.com/dipu-bd/lightnovel-crawler/blob/master/VERSION)

Crawls light novels and make text, epub and mobi

## Tutorial

### Installation

Make sure that you have `python3` and `pip` installed in your computer. Add this package using:

```bash
$ pip install lightnovel-crawler

# Or if it does not work, use:
$ python3 -m pip install --user lightnovel-crawler
```

Next, *Open the console panel in a directory you want to store your downloaded novels* and
run the following to open an interactive console.

```bash
$ lightnovel-crawler

# Or, a shortcut:
$ lncrawl
```

To view more logs, there is a verbose mode:
```bash
$ lncrawl -v
```

### Additional dependencies

#### For MOBI Output

- KindleGen: https://www.amazon.com/gp/feature.html?docId=1000765211

#### NodeJS for cloudflare

Some websites like `novelplanet` needs `nodejs`. Install it from:

- Downloads: https://nodejs.org/en/download/ 
- Linux: `curl -sL https://deb.nodesource.com/setup_8.x -o nodesource_setup.sh`

### Available websites

The list of crawable websites are given below. *Request new site by [creating a new issue](https://github.com/dipu-bd/lightnovel-crawler/issues)*.

- https://lnmtl.com
- https://www.webnovel.com
- https://www.wuxiaworld.com
- https://www.wuxiaworld.co
- https://boxnovel.com
- https://www.readlightnovel.org
- https://novelplanet.com
- https://lnindo.org
- https://www.idqidian.us

## Adding new source

- Use the [`_sample.py`](https://github.com/dipu-bd/lightnovel-crawler/blob/master/lightnovel_crawler/_sample.py) as blueprint.
- Add your crawler to [`__init__.py`](https://github.com/dipu-bd/lightnovel-crawler/blob/master/lightnovel_crawler/__init__.py).

That's all!
