# Introduction

# Import osm data

```bash
./utils/setup.php --osm-file ~/2015-12-09.osm.pbf --all --osm2pgsql-cache 18000 2>&1 | tee setup.log
```

#Diff update

```bash
./utils/update.php --import-file ~/2015-12-16.osm.pbf
./utils/update.php --index
```
