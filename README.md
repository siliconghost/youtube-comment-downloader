# youtube-comment-downloader
Simple script for downloading Youtube comments without using the Youtube API. The output is in line delimited JSON.

### Dependencies
* Python 3.6+
* requests
* lxml (A binding for the libxml2 and libxslt libraries - http://www.lfd.uci.edu/~gohlke/pythonlibs/#lxml)
* cssselect

The python packages can be installed with

    pip install requests
    pip install lxml
    pip install cssselect

### Usage
```
usage: downloader.py [--help] [--youtubeid YOUTUBEID] [--output OUTPUT]

Download Youtube comments without using the Youtube API

optional arguments:
  --help, -h            Show this help message and exit
  --youtubeid YOUTUBEID, -y YOUTUBEID
                        ID of Youtube video for which to download the comments
  --output OUTPUT, -o OUTPUT
                        Output filename (output format is line delimited JSON)
```
