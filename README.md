# hadoop-spark

#JAVA

export JAVA_HOME=/usr/local/jdk

export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar

export PATH=$JAVA_HOME/bin:$PATH

#scala

export SCALA_HOME=/usr/local/scala

export PATH=$SCALA_HOME/bin:$PATH

#hadoop

export HADOOP_HOME=/usr/local/hadoop

export PATH=$HADOOP_HOME/bin:$HADOOP_HOME/sbin:$PATH

#export HADOOP_CONF_DIR=$HADOOP_HOME/etc/hadoop

#export YARN_CONF_DIR=$HADOOP_HOME/etc/hadoop

#spark

export SPARK_HOME=/usr/local/spark

export PATH=$SPARK_HOME/bin:$PATH

export PYTHONPATH=$SPARK_HOME/python:$SPARK_HOME/python/lib/py4j-0.10.7-src.zip:$PYTHONPATH     #py4j

export PATH=$SPARK_HOME/python:$PATH



ssh
ssh-keygen -t rsa -P ''

cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys



关闭防火墙

systemctl stop firewalld.service

systemctl disable firewalld.service
