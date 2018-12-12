# art-museum-dbms
A database management system web application for managing art museum data

## Run application
* Connect to the VM instance from terminal:
```
$ gcloud compute ssh --project cs4111
```

* Run the application on the Google Cloud Compute Engine:
```
$ cd ~/art-museum-dbms
$ python server.py
```
The application is running on:
```
http://35.237.45.106:8111/
```

Run the application locally on:
```
http://0.0.0.0:8111/
```

## Update database
* Connect to the PostgreSQL database server:
```
$ psql -U ww2505 -h 35.237.206.133 -d proj1part2
```
