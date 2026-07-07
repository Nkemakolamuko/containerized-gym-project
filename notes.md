## Data directory of the database you are using determines where the data lives

``` 
  Just google it
  Based on your OS
  Linux uses /var/lib/mysql if you are using 
  mysql though and so on
```

### The above helps in persisting data even after you run:
`docker compose down`

>The above helps persist data accross getting a container up or down

### With bind mounts, we can make the container have access to the actual source code on our machine, but the one that exist in the image. That way, when we edit our file and save, the UI is updated automatically without needing a new build.
