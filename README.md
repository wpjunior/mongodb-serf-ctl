mongodb-serf-ctl
----------------
A controller for mongodb cluster with serf.

Requirements
------------
* Docker

Instalation
-----------

with root user:

```bash
cd /usr/bin/
wget https://raw.githubusercontent.com/wpjunior/mongodb-serf-ctl/master/mongodb-serf-ctl
chmod +x mongodb-serf-ctl
```

Getting started
---------------

1. Build the image (from: https://github.com/wpjunior/mongodb-serf)

```bash
mongodb-serf-ctl build
```

2. Start first cluster

```bash
mongodb-serf-ctl start
```

3. show cluster members

```bash
mongodb-serf-ctl status
```

4. add more one router (mongos)

```bash
mongodb-serf-ctl start_router02
```

4. add more one replicaset (mongod)

```bash
mongodb-serf-ctl start_rs3
```

5. connect to mongodb shell

```bash
mongodb-serf-ctl shell
```
