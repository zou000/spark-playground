# spark-playground

playground for exploring Spark DataFrames and Spqrk SQL

1. clone the repo:
```
git clone git@github.com:zou000/spark-playground.git $HOME/git/spark-playground
```
2. run docker image, it will pull the image if it is the first time.
```
docker run --rm -p 8888:8888 -p 4040:4040 -p 4041:4041 -v $HOME/git/spark-playground:/v -w /v jupyter/all-spark-notebook
```  
3. copy the url `http://127.0.0.1:8888/?token=xxxx` line from the docker console and open it from a browser
4. click the `spark.ipynb` notebook

### Notes
* docker image described in https://jupyter-docker-stacks.readthedocs.io/en/latest/using/specifics.html#apache-spark
* dataset copied from https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset
*  DataFrame(DataSet) API: https://spark.apache.org/docs/latest/api/scala/org/apache/spark/sql/Dataset.html 
