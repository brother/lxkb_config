AM_CPPFLAGS = -DLOCALEDIR=\"$(localedir)\"

bin_PROGRAMS = lxkb_config
lxkb_config_SOURCES=\
    system.h \
    config.h \
    gettext.h \
    xkblib_interface.c \
    setxkbmap_interface.c \
    manage_user_preferences.c \
    manage_rules.h \
    manage_desktop_preferences.c \
    manage_xorg_rules.c \
    data_structures.h \
    manage_user_preferences.h \
    manage_xorg_preferences.c \
    setxkbmap_interface.h \
    gtk+2.x_tab_page_layouts.c \
    gtk+2.x.h \
    gtk+2.x_tab_page_others.c \
    gtk+2.x_tab_page_about.c \
    gtk+2.x.c \
    main.c

INCLUDES = @GTK2_CFLAGS@ @GLIB2_CFLAGS@  @LIBXML2_CFLAGS@
lxkb_config_LDADD = @GTK2_LIBS@ @GLIB2_LIBS@ @LIBXML2_LIBS@
