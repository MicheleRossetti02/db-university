SELEZIONO GLI STUDENTI NATI NEL 1990 (160)
```sql
SELECT * FROM `students` WHERE date_of_birth BETWEEN "1990-01-01" AND "1990-12-31";
```

SELEZIONO TUTTI I CORSO DI LAUREA CHE VALGONO PIU' DI 10 CREDITI (469)

```sql
SELECT * FROM `courses` WHERE cfu > 10;
```

SELEZIONO TUTTI GLI STUDENTI CON PIU' DI 30 ANNI (3489)
```sql
SELECT * FROM `students` WHERE date_of_birth <= "1992-12-06";
```


SELEZIONO TUTTI I CORSI DEL PRIMO SEMESTRE DEL PRIMO ANNO DI QUALSIASI CORSO DI LAUREA (286)
```sql
SELECT * FROM `courses` WHERE `period` = 'I semestre ' AND year = 1;
```


SELEZIONO TUTTI GLI APPELLI DI ESAME SVOLTI NEL POMERIGGIO DOPO LE 14 DEL 20/06/2020 (21)
```sql
SELECT * FROM `exams` WHERE `date` ="2020-06-20" AND hour >= "14:00:00";
```


SELEZIONO TUTTI I CORSI DELLA LAUREA MAGISTRALE (38)
```sql
SELECT * FROM `degrees` WHERE `level`= "magistrale";

```

SELEZIONI I DIPARTIMENTI DA CUI E' COMPOSTA L'UNIVERSITA' (12)
```sql
SELECT * FROM `departments`;
```

SELEZIONI GLI INSEGNANTI CHE NON HANNO UN NUMERO DI TELEFONO(50)
```sql
SELECT * FROM `teachers` WHERE `phone` is NULL;
```







