# Permiso-de-carpetas-y-archivos

```

chown www-data:www-data  -R * # Let Apache be owner
find . -type d -exec chmod 755 {} \;  # Change directory permissions rwxr-xr-x
find . -type f -exec chmod 644 {} \;  # Change file permissions rw-r--r--

find . -type d -exec chgrp paiscomd {} \;
find . -type f -exec chgrp paiscomd {} \;

find . -type d -exec chown paiscomd {} \;
find . -type f -exec chown paiscomd {} \;

```
