# Modifier la langue dans un programme {#core-ref:1d2f5742-4171-11e3-9773-cffb8e583c34}

Par défaut, le catalogue correspondant à la locale de l'utilisateur connecté est
chargé. Il est possible de changer le catalogue en cours d'exécution en
utilisant la fonction `setLanguage`.

    [php]
    setLanguage('fr_FR');
    print ___("Hello", "tstCtx");
    // => Bonjour à tous
    setLanguage('en_US');
    print ___("Hello", "tstCtx");
    // => Hello everybody

Le paramètre doit être la locale complète sur cinq lettres.


<!-- link -->
[wikiGettext]:       http://fr.wikipedia.org/wiki/GNU_gettext "Gettext sur Wikipédia"
[phpGettext]:        http://www.php.net/manual/fr/function.gettext.php "gettext sur php.net"
[actions]:           #core-ref:e67d8aeb-939c-46e3-9be8-6fc3ba75ebc2 "Action Dynacase"
[wsh]:               #core-ref:4df1314f-9fdd-4a7f-af37-a18cc39f3505 "Script Dynacase"
[gencatalog]:        #core-ref:2c163f00-8e94-4736-86f2-bb51352c52aa
[pgettext]:          http://www.gnu.org/software/gettext/manual/html_node/Contexts.html "Contexte dans gettext"
[ngettext]:          http://www.php.net/manual/fr/function.ngettext.php "ngettext sur php.net"
[layout]:           #core-ref:5f4a2f4b-9ceb-42db-8ac1-2a7baa621ce2
[xgettext]:         http://www.gnu.org/software/gettext/manual/html_node/xgettext-Invocation.htm "xgettext reference"
[famdecl]:          #core-ref:cfc7f53b-7982-431e-a04b-7b54eddf4a75
[gettextutil]:      http://www.gnu.org/software/gettext/manual/html_node/index.html#Top