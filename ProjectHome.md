# What is it? #
A library written in java, to help visualize data structures. Mainly, but not only, for debugging purposes. Originaly, this started for helping the debugging of Red Black trees, and it evolved much since then.

#### Example Output: ####
![http://3.bp.blogspot.com/_zq7QrjMjH0Y/TREE0fVf4WI/AAAAAAAAASk/qJ1BtjFtO7k/s800/RBTree_And_BinomialHeap.png](http://3.bp.blogspot.com/_zq7QrjMjH0Y/TREE0fVf4WI/AAAAAAAAASk/qJ1BtjFtO7k/s800/RBTree_And_BinomialHeap.png)

## How does it work? ##
The library connects to existing data structures with minimal to no effort (depending on how "nice" is the structure) using either reflection or interfaces. Parsing of certain text formats is also supported.

Currently, only data structures which can be represented as directed-tree graphs are supported. Support for Direct-Acyclic-Graphs (DAGs) and general Graphs is on the way!

## Where do I get it? ##
See the [downloads page](http://code.google.com/p/structure-graphic/downloads/list). You want the ZIP files (which contain inside them a Java JAR file).

## How do I use it? ##
Download the official manual from the [downloads page](http://code.google.com/p/structure-graphic/downloads/list). You want the PDF file.

### Source code: Checking out the source code of the library ###
Take a look at the [Source Checkout](http://code.google.com/p/structure-graphic/source/checkout) page for more information. Basically, the current source is a [Nebeans](http://netbeans.org/) project hosted in a [SVN](http://en.wikipedia.org/wiki/Apache_Subversion) repository.

---

#### About: The background that lead me to write the library ####
This library is being written in Java as part of my learning about how to view and edit data. I know from personal expirience that there is a need to debug data structures graphically sometimes, and this library collects some of the visualization techniques I developed.

Another motivator to write this library was the idea of writing a node-editor for [GEGL](http://gegl.org/). I realized that I need algorithms to visualize graphs (I can't just open a graph with randomly located nodes - it will look terrible).