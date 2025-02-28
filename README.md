[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ULiw8LbN)
# Exercici 1
Al primer exercici he explicat les comandes de Linux les cuals serveixen per analitzar logs.

# Exercici 2
Al exercici 2 el que he fet a sigut utilitzar la llibreria logging per guardar errors a un arxiu. Primer de tot he configurat el logger, amb el error_handler puc manejar els errors, amb el info_handler puc manejar l'informació, amb el console_handler puc manejar la consola. Un cop tenim els handlers els affegim al logger perque aquest els pugi utilitzar. Pasem el logger en format csv, fen un bucle generem info i errors perque es guardin al csv i als altres fitxers.

|                           | Llenguatge 1 | Llenguatge 2 | Altre (opcional) |
|---------------------------|-------------|-------------|------------------|
| **Llenguatge**            |   Python          |   Dart          |    Java              |
| **Nom de la llibreria**   |   Logging          |        logger     |        Logback          |
| **És nativa del llenguatge?** |   si      |      No       |        No          |
| **URL per descarregar-se la llibreria** | Esta inclossa amb python |    Nomes fa falta afeggir la dependecia    |        https://logback.qos.ch/          |
| **Inicialització de l’objecte de logger** |logger = logging.getLogger('nom') | var logger() = Logger()        | Logger logger = LoggerFactory.getLogger(Classe.class)                 |
| **Nivells de log disponibles** |   DEBUG, INFO, WARNING, ERROR, CRITICAL     |    Fine,Finer,FINEST,INFO,WARNING,SEVERE,SHOUT         |   TRACE, DEBUG, INFO, WARN, ERROR	               |
| **Mètode per fer log**    |    logger.info("Missatge")	         |      logger.fine("MISSATGE")       |       logger.info("Missatge")	           |
| **Tipus de manejadors (pantalla, fitxer...) Identificar els seus noms a la API** |FileHandler, StreamHandler, RotatingFileHandler, etc. | ConsoleHandler, FileHandler, RemoteHandler |ConsoleAppender, FileAppender, RollingFileAppender, etc.	 |
| **Opcions de format**     |    Format per defecte o personalitzat amb Formatter.         | En Dart, quan utilitzes la biblioteca `logging`, el format per defecte dels missatges de log és bastant senzill i inclou la informació bàsica com el nivell de log, el missatge i la data/hora. No obstant això, no hi ha un `Formatter` predefinit en la biblioteca `logging`, així que el format per defecte es basa en la implementació que facis al teu manejador de logs.            |       Configuració amb patrons a logback.xml.	           |