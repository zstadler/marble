#Marble maps
This repository holds map definitions for Marble.

###Usage
* Compressed files

    uncompress an archive file according to [Marble paths](https://techbase.kde.org/Projects/Marble/CustomMaps)

* raw files

    copy earth/${url} under [Marble paths](https://techbase.kde.org/Projects/Marble/CustomMaps)
    copy  every path defined in earh/${url}/${url}.dgml (inside sourcedir) under Marble paths.

example: 
for osm.org.il working on GNU/linux.


earth/osm.org.il/osm.org.il.dgml has 3 subdirs defined:
```xml
          <sourcedir format="PNG"> earth/osm.org.il </sourcedir>
          <sourcedir format="PNG"> earth/routes </sourcedir>
          <sourcedir format="PNG"> earth/mtb </sourcedir>
```

copy earth/osm.org.il , earth/routes, and earth/mtb to /usr/share/marble/data/maps/
