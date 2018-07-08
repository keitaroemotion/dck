dck
======

easy alias script to make docker command more easy to use.


installation
------

```
$ ./installer
```


usage
------

### show help menu

```
$ dck -h
```

### kill docker image with image id

```
$ dck -k [image_id] 
```

The image_id above can be parital input. For instance, if the image id to kill is `95da73ea770dk`, you can put it as:

```
$ dck -k 95da
```

### show docker images with key word

```
$ dck -l [keyword]
```
