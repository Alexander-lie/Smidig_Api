# API til smidig
Har spørsmål til quiz, og lagrer brukere/sjekker om de logger inn med riktig passord.


```GET quiz```

Returnerer spørsmål som et array med objekter


`POST user`

tar i mot json object, lagres så i database.


`POST login`
tar i mot JSON object, returnerer 200 hvis login er riktig. Ellers 401.

