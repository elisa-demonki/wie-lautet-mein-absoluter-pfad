# Wie lautet mein absoluter Pfad?

Lade die pfad.php auf deinen Webspace und rufe diese auf. 

Daraufhin erhälst du deinen absoluten Pfad.

/* Der Pfad kann beispielsweise in der _wp-config.php_ eingefügt werden, so dass statt der Ordner _wp-content_ der Ordner _dateien_ von WordPress genutzt wird. (Achte dabei darauf, dass du den Ordner _wp-content- händisch umgenannt hast.) */

`define('WP_CONTENT_DIR', '/absoluter-pfad/dateien');`

`define('WP_CONTENT_URL', 'http://www.meine-website.de/dateien');`
