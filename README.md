fbStalker - OSINT tool for Facebook - Based on Facebook Graph and other stuff


geoStalker - OSINT tool for Geolocation related sources - Flickr, Instagram, Twitter, Wigle. The userIDs found is used to find social media accounts across other networks like Facebook, Youtube, Instagram, Google+, Linkedin and Google Search

Instructions - Work in Progress

Both scripts require python2.6. Other versions of python has not been tested.

Dependencies for Geostalker 
[Tested on Kali Linux]

wget https://pypi.python.org/packages/source/p/pip/pip-1.4.1.tar.gz
tar xvfz pip-1.4.1.tar.gz
cd pip-1.4.1
sudo python2.6 setup.py install

git clone https://github.com/hadim/pygraphml.git
cd pygraphml
python2.6 setup.py install

pip install google
pip install python-instagram
pip install pygoogle
pip install geopy
pip install lxml
pip install oauth2
pip install python-linkedin
pip install pygeocoder
pip install selenium
pip install termcolor
pip install pysqlite
pip install TwitterSearch
pip install foursquare


wget https://gdata-python-client.googlecode.com/files/gdata-2.0.18.tar.gz
tar xvfz gdata-2.0.18.tar.gz
cd gdata-2.0.18
python2.6 setup.py install

