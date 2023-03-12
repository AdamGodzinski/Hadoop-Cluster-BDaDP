# Hadoop-Cluster-BDaDP

1.clone github repository

git clone https://github.com/AdamGodzinski/Hadoop-Cluster-BDaDP.git

2. create hadoop network

sudo docker network create --driver=bridge hadoop

3. Build container image

sudo docker build . -t hadoopCluster

4. Remember to configure files
