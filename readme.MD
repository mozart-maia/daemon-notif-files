Para criar um novo build rode o seguinte commando no terminal dentro da pasta raiz do projeto:

'''gcc -Wall -pedantic -std=gnu99 -o build/rolexhound rolexhound.c $(pkg-config --cflags gdk-pixbuf-2.0 libnotify) -lnotify'''

