gcc hello.c -o hello $(pkg-config allegro-5 allegro_font-5 allegro_main-5 --libs --cflags)
