# xmllint & xmlstarlet demo

> A simple bash script to explore xmllint & xmlstarlet usage

[xmllint Documentation](http://www.xmlsoft.org/xmllint.html)<br />
[xmlstarlet Documentation](http://xmlstar.sourceforge.net/docs.php)<br />

### Installation for xmllint
Mac OS X (Yosemite) installed by default<br/>

    Ubuntu: sudo apt-get install libxml2-utils


### Installation for xmlstarlet
    For Mac: brew install xmlstarlet
    For Ubuntu: sudo apt-get install xmlstarlet

### xmllint usage demos in this project
1. --xpath
2. --repeat
3. --timing

### xmlstarlet usage demos in this project
1. -el
2. -el -a
3. -el -v
4. -ed -d
5. -ed -u

### Running the demo

Project includes below sample xml file<br/>
[books.xml](data/books.xml)<br/>

### To run xmllint demo script:
    ./xmllint-demo.sh data/books.xml


### To run xmlsartlet demo script:
    ./xmlstarlet-demo.sh data/books.xml
