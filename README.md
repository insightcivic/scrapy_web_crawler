# scrapy_web_crawler

## What are we doing

Scraping a website using Scrapy.

## About Scrapy

Scrapy (/ˈskreɪpaɪ/) is an application framework for crawling web sites and extracting structured data which can be used for a wide range of useful applications, like data mining, information processing or historical archival.

Even though Scrapy was originally designed for [web scraping](https://en.wikipedia.org/wiki/Web_scraping), it can also be used to extract data using APIs (such as [Amazon Associates Web Services](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html)) or as a general purpose web crawler.

Scrapy is written in pure Python and depends on a few key Python packages (among others):

- [lxml](https://lxml.de/index.html), an efficient XML and HTML parser
- [parsel](https://pypi.org/project/parsel/), an HTML/XML data extraction library written on top of lxml,
- [w3lib](https://pypi.org/project/w3lib/), a multi-purpose helper for dealing with URLs and web page encodings
- [twisted](https://twistedmatrix.com/trac/), an asynchronous networking framework
- [cryptography](https://cryptography.io/en/latest/) and [pyOpenSSL](https://pypi.org/project/pyOpenSSL/), to deal with various network-level security needs


>[!info] BeautifulSoup versus Scrapy; Scrapy is the better  choice, since BS4 is more of a parser than a scraper.


## Virtual Environment Setup

```bash
# create virtual environment

conda create -y -n scrapy [python=3.10]
conda info --env # to check 

cd c:\scrapy

# acivate virtual environment
conda activate scrapy

```

### Install dependencies

```bash
conda install -y pandas jupyter matplotlib 

# install scrapy and  dependencies 
conda install -c conda-forge scrapy

```

