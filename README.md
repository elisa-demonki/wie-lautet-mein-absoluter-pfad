# Wie lautet mein absoluter Pfad?

Lade die pfad.php auf deinen Webspace und rufe diese auf. 

Daraufhin erhälst du deinen absoluten Pfad.

/* Der Pfad kann beispielsweise in der _wp-config.php_ gebraucht werden, so dass WordPress statt den Ordner _wp-content_ den Ordner _dateien_ verwenden könnte. (Achte dabei darauf, dass du den Ordner _wp-content_ händisch umbenennen musst.) */

`define('WP_CONTENT_DIR', '/absoluter-pfad/dateien');`

`define('WP_CONTENT_URL', 'http://www.meine-website.de/dateien');`
