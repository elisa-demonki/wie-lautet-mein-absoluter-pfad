# Wie lautet mein absoluter Pfad?

Lade die pfad.php auf deinen Webspace und rufe diese auf. 

Daraufhin erhälst du deinen absoluten Pfad.

![picture alt](http://i.giphy.com/XG6yirnUOL744.gif "Quelle: imgur.com")
> Quelle: imgur.com


### Wozu braucht man das?

Der Pfad wird gebraucht, wenn statt der Ordner _wp-content_ der Ordner _dateien_ verwendet werden soll.

`define('WP_CONTENT_DIR', '/absoluter-pfad/dateien');`

`define('WP_CONTENT_URL', 'http://WEBSITE.EXAMPLE/dateien');` 

