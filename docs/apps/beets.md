**Music library manager and MusicBrainz tagger**

After install just run the following command to update your current library :
```docker exec -u 1000:1000 -it beets /bin/bash -c 'beet import /music'```

Where 1000:1000 is Username or UID (format: <name|uid>[:<group|gid>]) and ```/music``` where your libary is store.

To import from an other folder to your folder library just change ```/music```
**Don't excpect to manage your library with the web interface...**
