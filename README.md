#Data Hustling with Spark

####*Mashed Up in Spark, Python and a JSON dump from MongoDB*

This is a project the involves data exploration of various twitter users following a local music artist

Data has been gathered from a Twitter ETL process that gathered profile information about Twiiter users and stored it in a MongoDB database. 
The information was then exported to a JSON file that could be ingested by a stand alone instance of Spark.

Data was also gathered from Server log files associated with the artists website and ingested into Spark to analyze.

The .json and .txt files used above have been provided so that if you have an instance of Spark running and IPython Noteebook available you can examine various ways of interacting with Spark

Ipyton notebook and Spark can be started as follows depending where you pyspark is located:

`IPYTHON_OPTS="notebook --pylab inline" ./bin/pyspark`

[View the notebook in a browser human readable format](http://nbviewer.ipython.org/github/rcchirwa/PySpark-Hustling/blob/master/PySpark_and_JSON.ipynb)

This will launch an instance of ipython notebook with the Spark Context available to you in the notebook