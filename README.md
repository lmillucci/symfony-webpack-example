# Applicazione d'esempio della gestione del front-end con Symfony

Questo repository contiene il codice sorgente di un'applicazione Symfony il cui codice sorgente è gestito tramite `webpack-encore`.
Per avere una spiegazione dettagliata sul funzionamento di Symfony e webpack ti rimando al [post del blog](https://www.lorenzomillucci.it) associato a questo repository

## Installazione

NOTA: per usare questo progetto è necessario usare la [Symfony CLI](https://symfony.com/doc/master/cloud/getting-started#installing-the-cli-tool). Assicurati di installarla.

- Installare le dipendenze PHP con il comando `composer install`
- Installare le dipendenza Javascript con il comand `yarn install`
- Creare gli asset con il comando `yarn encore dev`
- Avviare il progetto con il comando `symfony serve -d`
- Collegarsi all'indirizzo `http://127.0.0.1:8000`
