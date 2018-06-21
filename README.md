# C4E-Notebooks

Here are gathred [SparkNotebook](https://github.com/spark-notebook/spark-notebook) exposing example of use from [Clustering4Ever](https://github.com/Clustering4Ever/Clustering4Ever) library.

# Install spark-notebook in your PC
Interactive and Reactive Data Science using Scala and Spark provided by [kensu.io](https://www.kensu.io/)

### Optional 
* Install  [virtual box](https://www.virtualbox.org/) with Ubuntu or Debian.
Before starting the virtual machine to make sure to increase the memory and the number of processors
* Install Java  -> sudo apt-get install default-jre

### Download the latest version on : http://spark-notebook.io/
* Step 1>  You must enter your email, so a download link will be sent to you (master version)
<img src="https://82568e45-a-62cb3a1a-s-sites.googlegroups.com/site/lebbah/datatp/sparkSNB.png?attachauth=ANoY7crXLXLAyuINafKX7XT-dD8jwW5bceePcY2jaw1X_3w0meudInyt0oXTj98JkkjvXOyedhO758g5h2jikxU9Vml6UQQPcv5SfW_wANpgKTxO8tfysPGgkk-3sbBuDbHgP87QXtm6l6eafaNglTrCVinCADvkLvI-kt3D-7bMA51LuDuPZRUV6t_p17h-fYMVz2aqIWRHjXxHIIP6sR1qIJIFnBxKlg%3D%3D&attredirects=0" width="450" height="230" border="0">

* Step 2> unzip Title.zip
* Step 3> cd Title
* Step 4> ./bin/spark-notebook    
  Some times you need before to run chmod +x ./bin/spark-notebook

* Step 5> Open the web browser and launch this address : http://localhost:9001
  or
  http://localhost:9000
  
* Step 6> import "snb" or "snb.ipynb" file using your browser 
<img src="https://sites.google.com/site/lebbah/aims-program/openspark.png" width="400" height="218" border="0">
Some examples are avalaible via this link: https://github.com/Spark-clustering-notebook/Clustering4Ever-Notebooks/tree/master/SparkNotebooks 

To learn about Scala you can download your JustEnoughScala.snb  (provided by Kensu.io)

### Additional informations 
* To change port number if it is necessary
(/bin/spark-notebook -Dhttp.port=8888)
* Edit Notebook Metadata if you want to add/modify API version


    Example :  add smile API 
   "customDeps": [
    "com.github.haifengl:smile-scala_2.11:1.4.0"
  ],

## Citation
If you publish material based on informations obtained from this repository, then, in your acknowledgements, please note the assistance you received by using this community work. This will help others to obtain the same informations and **replicate your experiments**, because having results is cool but being able to compare to others is better.
Citation: `@misc{C4E, url = “https://github.com/Clustering4Ever/Clustering4Ever“, institution = “Paris 13 University, LIPN UMR CNRS 7030”}`
