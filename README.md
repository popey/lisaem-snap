Fails to build...

```
/root/parts/wx/build/bk-deps gcc -c -o wxregex_regfree.o -DNDEBUG -D__WXGTK__   -D_FILE_OFFSET_BITS=64 -DwxDEBUG_LEVEL=0 -I/root/parts/wx/build/lib/wx/include/gtk2-unicode-static-3.1 -I./include -pthread -I/usr/include/gtk-2.0 -I/usr/lib/x86_64-linux-gnu/gtk-2.0/include -I/usr/include/gio-unix-2.0/ -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng16 -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/pango-1.0 -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -pthread -I/usr/include/gstreamer-1.0 -I/usr/include/orc-0.4 -I/usr/include/gstreamer-1.0 -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -DG_DISABLE_CAST_CHECKS -pthread -Wall -Wundef -O2 -pthread -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng16 -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -pthread -I/usr/include/gtk-unix-print-2.0 -I/usr/include/gtk-2.0 -I/usr/lib/x86_64-linux-gnu/gtk-2.0/include -I/usr/include/gio-unix-2.0/ -I/usr/include/cairo -I/usr/include/pango-1.0 -I/usr/include/atk-1.0 -I/usr/include/cairo -I/usr/include/pixman-1 -I/usr/include/gdk-pixbuf-2.0 -I/usr/include/libpng16 -I/usr/include/pango-1.0 -I/usr/include/harfbuzz -I/usr/include/pango-1.0 -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -D_GNU_SOURCE -fPIC  ./src/regex/regfree.c
In file included from ./include/wx/platform.h:518:0,
                 from ./include/wx/defs.h:45,
                 from ./src/regex/regcustom.h:39,
                 from ./src/regex/regguts.h:38,
                 from ./src/regex/regexec.c:32:
./include/wx/chkconf.h:1472:13: error: #error "wxUSE_DYNAMIC_LOADER requires wxUSE_DYNLIB_CLASS."
 #           error "wxUSE_DYNAMIC_LOADER requires wxUSE_DYNLIB_CLASS."
```
