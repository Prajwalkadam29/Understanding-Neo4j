## Creating the Data:

The Cypher `CREATE` clause is used to create data in your graph. If you are not familiar with Cypher syntax, you can try the Query fundamentals guide.

```
CREATE CONSTRAINT movie_title IF NOT EXISTS FOR (m:Movie) REQUIRE m.title IS UNIQUE;
CREATE CONSTRAINT person_name IF NOT EXISTS FOR (p:Person) REQUIRE p.name IS UNIQUE;
```

## Merging the data:

```


```
