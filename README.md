<h1>Description</h1>
This project is about finding a profitable 
forecasting trading strategy 
on the FOREX market on historical data, and use the historical data to train a naive bayes classifier. The classifier should then make a prediction on whether, the next trade you enter should be a long or a short position. In order to minimize the scop of the project, we have choosen to limit ourself to only use data and trade on the EUR/USD currency pair

<h2>Requirements</h2>
<ul>
	<li>Python2.7</li>
	<li>TA-Lib already installed on the pc</li>
	<li>TA-Lib python wrapper</li>
	<li>nltk</li>
</ul>

The TA-Lib can be found and downloaded from the following site: [TA-Lib](http://ta-lib.org/hdr_dw.html)
<br />
The TA-Lib python wrapper can be found at the following github site: https://github.com/mrjbq7/ta-lib
<br />
if you just want to install it on your machine you can install it from PyPI:
"$easy_install TA-Lib"
<br />
or use 
"$pip install TA-Lib"
<br />
<br />


<h3>Short guide on how to install TA-Lib on the different OS</h3>
##### Mac OS X

```
$ brew install ta-lib
```

##### Windows

Download [ta-lib-0.4.0-msvc.zip](http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-msvc.zip)
and unzip to ``C:\ta-lib``

##### Linux

Download [ta-lib-0.4.0-src.tar.gz](http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz) and:
```
$ untar and cd
$ ./configure --prefix=/usr
$ make
$ sudo make install
```

<h3>installing the nltk</h3>
To install the nltk package in your python environment simply type 
```
$ pip install nltk
```
or 
```
$ easy_install nltk
```