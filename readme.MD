To create a new build, run the following command in the terminal within the project root folder:

```gcc -Wall -pedantic -std=gnu99 -o build/rolexhound rolexhound.c $(pkg-config --cflags gdk-pixbuf-2.0 libnotify) -lnotify```

