# Sublime Text 2 plugin - Cypher

A plugin for working with [Neo4j](http://www.neo4j.org)'s [Cypher](http://docs.neo4j.org/chunked/milestone/cypher-query-lang.html) query language in [SublimeText](http://www.sublimetext.com).

# Fork differences

* Contains the Cypher 4.1 keywords and functions
* Contains the UTF-8 Fix from [fredbenenson](https://github.com/fredbenenson/sublime-cypher)

# Installation - Sublime Text 2

* If you don't have it already install [Sublime Package Control](http://wbond.net/sublime_packages/package_control)
* See [Package Control usage](http://wbond.net/sublime_packages/package_control/usage)
* Open the Command Pallete (`CTRL+SHIFT+P`)
* Select "Install Package"
* Select "Cyper"

The plugin will detect files ending in `.cql` or `.cyp` as Cypher, optionally just select Cypher from the Syntax menu. 

# Installation - Sublime Text 3

1. Download the [zip](https://github.com/cskardon/sublime-cypher/archive/master.zip) of this repository
2. Open Sublime Text 3, and go to ‘Browse Packages’ (`CTRL + SHIFT + P` then type ‘browse’ and hit ENTER)
3. Unzip the repository into that folder - (your packages folder should have new folder called 'Cypher' or something, )
4. Restart Sublime Text 3.
5. Open a file containing some Cypher queries and switch to Cypher mode (`CTRL + SHIFT + P` then type ‘Cypher’ and hit ENTER)


# Usage

* Type a Cypher query into your editor
* Run it by selecting the query and hitting (cmd+shift+r on OSX, ctrl+shift+r on Windows)
* The results or error will be shown in the console, which can be opened by (ctrl+`)
* If no text is selected, all the text in the file is run as a single query


# Future Plans

* Auto selecting the query under the cursor
* Auto completion for Cypher keywords and functions, etc
* Auto completion based on data in the DB
* Cypher 2 support

