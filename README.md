# hadoop-spark

#JAVA

export JAVA_HOME=/usr/local/jdk1.8.0_201

export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar

export PATH=$PATH:$JAVA_HOME/bin

#scala

export SCALA_HOME=/usr/local/scala

export PATH=$SCALA_HOME/bin:$PATH

#hadoop

export HADOOP_HOME=/usr/local/hadoop-2.7.7

export PATH="$HADOOP_HOME/bin:$HADOOP_HOME/sbin:$PATH"

export HADOOP_CONF_DIR=$HADOOP_HOME/etc/hadoop

export YARN_CONF_DIR=$HADOOP_HOME/etc/hadoop

#spark

export SPARK_HOME=/usr/local/spark-2.3.3-bin-hadoop2.7

export PATH="$SPARK_HOME/bin:$PATH"

export SPARK_HOME=/home/stj926/spark2.3.3/
export PATH=$SPARK_HOME/bin:$PATH
export PYTHONPATH=$SPARK_HOME/python:$SPARK_HOME/python/lib/py4j-0.10.7-src.zip:$PYTHONPATH
export PATH=$SPARK_HOME/python:$PATH
