[![](https://images.microbadger.com/badges/image/dongjoon/java8-hdw.svg)](https://microbadger.com/images/dongjoon/java8-hdw)
[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](LICENSE)

Hadoop Data Warehouse
====================

Components
----------
This is a reference model for Hadoop Data Warehouse.

* Debian 8.6
* Hadoop 2.7.3
* Spark 2.1.0
* Elasticsearch 2.4.3
* Hive 2.1.1
* Python 2.7.9
* IPython 5.1.0

Run
---
You can build and run a cluster easily.

> $ sudo docker pull dongjoon/java8-hdw

> $ bash -c "$(curl -fsSL https://raw.githubusercontent.com/dongjoon-hyun/dockerfiles/master/java8-hdw/run-cluster.sh)"

> ...

> $ root@hnn-001-01:~# ./test-hive.sh

> $ root@hnn-001-01:~# run-example SparkPi

> $ root@hnn-001-01:~# spark-shell

> $ root@hnn-001-01:~# ./run-ipython-notebook.sh

> ...

> $ root@hnn-001-01:~# exit
