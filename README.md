#Large Scale Machine Learning with Spark
This is the code repository for [Large Scale Machine Learning with Spark](https://www.packtpub.com/big-data-and-business-intelligence/machine-learning-spark?utm_source=github&utm_medium=repository&utm_campaign=9781783288519), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.
##Instructions and Navigations
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```

     [default] 
     SparkSession spark = SparkSession 
                            .builder() 
                            .appName("JavaFPGrowthExample") 
                            .master("local[*]") 
                            .config("spark.sql.warehouse.dir", 
     "E:/Exp/")                          .getOrCreate(); 

Or creating simple RDD from the input dataset is set as follows: 

     [default] 
                    String filename = “input/dataset.txt”; 
                    RDD<String> data = spark.sparkContext().textFile(fileName, 1); 

```

### Software requirements: 

Following software is required for chapters 1-8 and 10: Spark 2.0.0 (or higher), Hadoop 2.7 
(or higher), Java (JDK and JRE) 1.7+/1.8+, Scala 2.11.x (or higher), Python 2.6+/3.4+, R 3.1+, 
and RStudio 0.99.879 (or higher) installed. Eclipse Mars or Luna (latest) can be used. 
Moreover, Maven Eclipse plugin (2.9 or higher), Maven compiler plugin for Eclipse (2.3.2 or 
higher) and Maven assembly plugin for Eclipse (2.4.1 or higher) are required. Most 
importantly, re-use the provided pom.xml file with Packt's supplements and change the 
previously-mentioned version and APIs accordingly and everything will be sorted out. 

For Chapter 9, Advanced Machine Learning with Streaming and Graph Data, almost all the 
software required, mentioned previously, except for the Twitter data collection example, 
which will be shown in Spark 1.6.1. Therefore, Spark 1.6.1 or 1.6.2 is required, along with 
the Maven-friendly pom.xml file. 

### Operating system requirements: 

Spark can be run on a number of operating systems including Windows, Mac OS, and 
LINUX. However, Linux distributions are preferable (including Debian, Ubuntu, Fedora, 
RHEL, CentOS and so on). To be more specific, for example, for Ubuntu it is recommended 
to have a 14.04/15.04 (LTS) 64-bit complete installation or VMWare player 12 or Virtual 
Box.  For Windows, Windows (XP/7/8/10) and for Mac OS X (10.4.7+) is recommended. 

### Hardware requirements: 

To work with Spark smoothly, a machine with at least a core i3 or core i5 processor is 
recommended.  However, to get the best results, core i7 would achieve faster data 
processing and scalability with at least 8 GB RAM (recommended) for a standalone mode 
and at least 32 GB RAM for a single VM, or higher for a cluster. Besides, enough storage to 
run heavy jobs (depending upon the data size you will be handling), and preferably at least 
50 GB of free disk storage (for stand-alone and for SQL warehouse).

##Related Products
* [Fast Data Processing with Spark](https://www.packtpub.com/big-data-and-business-intelligence/fast-data-processing-spark?utm_source=github&utm_medium=repository&utm_campaign=9781782167068)

* [Machine Learning with Spark](https://www.packtpub.com/big-data-and-business-intelligence/machine-learning-spark?utm_source=github&utm_medium=repository&utm_campaign=9781783288519)

* [Large Scale Machine Learning with Python](https://www.packtpub.com/big-data-and-business-intelligence/large-scale-machine-learning-python?utm_source=github&utm_medium=repository&utm_campaign=9781785887215)
###Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781785888748">https://packt.link/free-ebook/9781785888748 </a> </p>