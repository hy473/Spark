
# 1. Installation

Before PySpark is installed, you must have Python and Spark.

**Step 1: Get Homebrew.**  

Homebrew is a package manager for macOS.
In order to install Homebrew, open your terminal and type:

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

In order to install Java, Scala, and Spark through the command line, we will probably need to install xcode-select. 
Go to terminal and type:

`xcode-select --install`

**Step 2: Get Apache Spark.**

* Install Java by Homebrew: `brew cask install java`
* Install Scala by Homebrew: `brew install scala`
* Install Apache Spark: `brew install apache-spark`
  * Run the Spark Shell: `spark-shell`


**Step 3: Get Python 3.**

* Install Python 3: `brew install python3`
* Install Jupyter: `pip3 install jupyter`
  * Run the notebook ~ `jupyter notebook`
* Install PySpark: `pip3 install pyspark`
  * Run the PySpark.

Note: In order to use PySpark with Python 3, go to terminal and type: `touch ~/.bash_profile; open ~/.bash_profile`.
Then, save `export PYSPARK_PYTHON=python3`.

**Step 4: Load PySpark using `findSpark` package.**
* Intall package `findspark`: `pip3 install findspark`
