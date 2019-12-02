# Allo !

J'suis Rosalie, j'viens du Québec là. J'ai 24 ans.

J'badtrippe un peu parce que j'suis nouvelle, mais on m'a dit d'pas trop m'en bâdrer.

Pour l'code j'suis pas trop bollée mais j'suis en bébitte boquée ! J'espère qu'vous allez pas trop me bourrasser quand même ^^ !

J'suis pas trop chialage ou chicane, j'suis plutôt colleuse et quand j'aime qqchose ou qqun, ça prend tout mon petit change !

En tout cas, j'espère me payer la traite en code avec vous les cheums !

J'vous donne un bec !

```
CREATE TABLE les_cheums
(
    id INT PRIMARY KEY NOT NULL,
    nom VARCHAR(100),
    prenom VARCHAR(100),
)
// écrire l'identité des cheums
ALTER TABLE les_cheums
ADD bec_check VARCHAR(255)
INSERT INTO les_cheums(bec_check)
VALUES('Fait "V"')
SELECT prenom FROM les_cheums WHERE bec_check = 'Fait "V"'

```

à tantôt les cheums ! 