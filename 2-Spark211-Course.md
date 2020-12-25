
https://phoenixnap.com/kb/install-spark-on-windows-10
https://github.com/cdarlint/winutils/tree/master/hadoop-3.2.1/bin
https://spark.apache.org/downloads.html


fault tolerance, throughput, and scalability that the Spark Core provides.
Java8 functional programming
Scala ...

Spark Fundamentals

Lesson 1 - Introduction to Spark - Getting started

        Understand and be able to explain the purpose of Spark
        List and describe the components of the Spark unified stack
        Understand the basics of Resilient Distributed Dataset (RDD)
        Download and install Spark standalone
        Scala and Python overview
        Launch and use Spark’s Scala and Python shell ©

Lesson 2 - Resilient Distributed Dataset and DataFrames

        Understand how to create parallelized collections and external datasets
        Work with Resilient Distributed Dataset (RDD) operations
        Utilize shared variables and key-value pairs

Lesson 3 - Spark application programming

        Understand the purpose and usage of the SparkContext
        Initialize Spark with the various programming languages
        Describe and run some Spark examples
        Pass functions to Spark
        Create and run a Spark standalone application
        Submit applications to the cluster

Lesson 4 - introduction to Spark libraries

        Understand and use the various Spark libraries such as SparkSQL, Spark Streaming, MLlib, and GraphX

Lesson 5 - Spark configuration, monitoring and tuning

        Understand components of the Spark cluster
        Configure Spark to modify the Spark properties, environmental variables, or logging properties
        Monitor Spark using the web UIs, metrics, and external instrumentation
        Understand performance tuning considerations

%env PYTHONPATH=%SPARK_HOME%\python;%SPARK_HOME%\python\lib\py4j--src.zip:%PYTHONPATH%

!pip install findspark 
!pip install 'pyspark==2.4.3' --force-reinstall 
import findspark 
import pyspark 
findspark.init() 
sc = pyspark.SparkContext.getOrCreate()

from pyspark import SparkConf, SparkContext​
sc = pyspark.SparkContext.getOrCreate()


!pip install findspark
!pip install pyspark
import findspark
# import pyspark
findspark.init()
from pyspark import SparkContext
sc = SparkContext.getOrCreate()

F4A10BAEC5B8FF1841F10651CAC2C4AA39C162D3
                               029CA180 A9749149 E6060805 B5B5DDF9 287B4AA3
                               21434810 172F8CC0 534943AC 005531BB 48B6622F
                               BE228DDC
C:\Users\SN\Downloads>certutil -hashfile spark-3.0.1-bin-hadoop2.7.tgz SHA512
SHA512 hash of spark-3.0.1-bin-hadoop2.7.tgz:
f4a10baec5b8ff1841f10651cac2c4aa39c162d 3029ca180a9749149e6060805b5b5ddf9287b4aa321434810172f8cc0534943ac005531bb48b6622fbe228ddc
CertUtil: -hashfile command completed successfully.


