# php_mssql_xdebug_composer
Mit dem Dockerfile wird mit dem Befahl 
      
    docker build https://github.com/taten-mit-daten/php_mssql_xdebug_composer.git#main -t taten-mit-daten/php-xdebug
ein Dockerimage für PHP 7.4 erzeugt, welches man zusammen mit einem nginx Webserver  verwenden verwenden kann. Zusätzlich zur Standartinstallation ist folgendes in PHP eingebunden:
- composer
- git
- xdebug
- sqlsrv Treiber für den Zugriff auf MSSQL Datenbanken, incl. "Hack" für den Zugriff auf ältere 2008er Server
