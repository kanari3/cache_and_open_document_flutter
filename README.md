# cache_and_open_document_flutter sample

Save temporary directory and open it!  
Support Android and iOS.

# cache directories
- Android (example)
```
/data/user/0/{APPLICATION_ID}/cache
```

- iOS
```
/data/Containers/Data/Application/{APPLICATION_ID}/Library/Caches
```

# Libraries
use the following
- path_provider
- open_file

# Unnecessary access control

Not required change AndoidManifest.xml and Info.plist.

# Note
The famous library `launch_url` did not work.
