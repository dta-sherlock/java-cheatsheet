# Java Cheat Sheet

## Java 8

### Les Streams

### Date Time API
``LocalDate result = LocalDate.of(2017, 2, 24);``

On peut récupérer les différents "membres", par exemple ``LocalDate.getYear()``

On peut récupérer une date à partir d'une String : ``LocalDate result = LocalDate.parse("217-02-24");``

On peut modifier uniquement l'année, par exemple : ``result.withYear(2016);``

Pour avoir la data courante : ``localDate.now()``

LocalTime pour heure/minute/seconde

LocalDateTime pour "combiner" les 2

## Test Unitaires

## Les logs

### Déclarer les logs

1. Ajouter les lignes suivantes dans le ```pom.xml```
2. En attribut static de la classe ajouter la ligne suivante :

```java
...
```

## Bonnes pratiques

## Accès aux données

### JDBC

### JPA

...
