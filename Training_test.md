r# PROMPTATHON

## Summary Bullet

### TEST 

Chers responsables du service client,
Je vous écris pour exprimer ma grande déception concernant mon compte bancaire. Malheureusement, les frais supplémentaires imprévus et les erreurs répétées dans mes relevés m'ont laissé une impression d'incompétence et de négligence de votre part. J'attends de ma banque un service fiable et transparent, ce qui n'a malheureusement pas été le cas jusqu'à présent. J'espère que vous prendrez rapidement des mesures pour résoudre ces problèmes et regagner ma confiance en tant que client. Votre prompte action est vivement souhaitée.
Cordialement,

### TRAINING

#### Input : 

Chère équipe du service client,
J'espère que ce courriel vous trouve bien. Je me permets de vous contacter aujourd'hui pour clarifier une situation concernant mon compte bancaire.
En consultant mon relevé de compte récent, j'ai remarqué la présence d'un découvert dont je n'ai pas connaissance. Étant donné que je suis très attentif à mes finances personnelles et que je veille à maintenir mon compte en bon état, cette découverte m'a surpris.
Je souhaiterais obtenir des informations supplémentaires sur les raisons de ce découvert. J'aimerais comprendre les frais qui y sont associés et les circonstances qui ont conduit à cette situation. Il est important pour moi d'avoir une vision claire de mes transactions et de pouvoir résoudre ce problème de manière adéquate.
De plus, je vous serais reconnaissant de bien vouloir m'indiquer les démarches nécessaires pour régulariser cette situation de découvert. Je suis disposé à prendre les mesures appropriées pour rétablir un solde positif dans les plus brefs délais.
Dans l'attente de votre réponse, je vous remercie par avance pour votre attention et votre assistance dans la résolution de cette situation. J'apprécie votre approche professionnelle et j'ai confiance en votre capacité à trouver une solution satisfaisante.
Cordialement,

#### Output : 

- Le client veut clarifier une situation concernant son compte bancaire
- Le client a pris connaissance d'un découvert
- Le client veut des informations supplémentaires sur les raisons du découvert
- Le client aimerait savoir les démarches pour régulariser cette situation

#### Input : 

Chère équipe du service client,
Je tiens à prendre quelques instants pour exprimer ma satisfaction et ma gratitude envers votre banque. En tant que cliente depuis plusieurs années, je suis extrêmement satisfaite de la qualité des services que j'ai reçus de votre part. Votre professionnalisme, votre efficacité et votre souci du détail ont contribué à rendre mes interactions avec votre établissement exceptionnelles.
Tout d'abord, je souhaite souligner l'excellence de votre service client. Chaque fois que j'ai eu une question ou besoin d'assistance, votre équipe s'est montrée disponible, amicale et compétente. Les conseillers ont toujours pris le temps de m'écouter attentivement et de répondre à mes préoccupations de manière claire et détaillée.
De plus, vos services en ligne sont d'une grande convivialité et d'une fiabilité exemplaire. La plateforme facilite la gestion de mes comptes, les transactions sont rapides et sécurisées, ce qui me donne une grande tranquillité d'esprit.
En outre, j'apprécie énormément la diversité des produits et des services que vous proposez. Votre banque offre une gamme complète de solutions financières adaptées à mes besoins, ce qui me permet de gérer mes finances de manière optimale.
Enfin, je tiens à souligner l'engagement de votre banque envers la communauté. Vos initiatives sociales et environnementales témoignent d'une responsabilité sociétale que je trouve admirable.
En conclusion, je tenais à vous adresser mes sincères félicitations pour la qualité de votre service bancaire. Votre équipe a su instaurer une relation de confiance avec moi en offrant un niveau de service exceptionnel. Je recommanderai volontiers votre banque à mon entourage et je suis fière de faire partie de votre clientèle.
Je vous souhaite une excellente continuation et je vous remercie chaleureusement pour votre dévouement et votre professionnalisme.
Cordialement,

#### Output : 

- La cliente exprime sa satisfaction
- La cliente est satisfaite du SAV
- La cliente est satisfaite des services en lignes
- La cliente est contente des offres qui sont complètes
- La cliente est contente des initiatives sociales et l'engagement de la banque



## NER

### TEST 

Bonjour, après le départ de nos enfants Eric et Lyse, ma femme Nathalie et moi avons décidé de lancer la rénovation de ma maison au 15 rue des carmes, 92005 Rififi Les Oies.je voulais convenir d'un rendez vous pour discuter des conditions d'un prêt, 
les premiers devis pour la toiture par Monsieur Duchamp sont de 15 456€ et 25 789€, également le rafraichissement des pièces du bas a été chiffré à 14 545€

### TRAINING

#### Input : 

« IBM est un concurrent de Google aux US» a déclaré Rami Swarthmore.

#### Output : 

IBM: company
Google: company
US: country 
Rami Swarthmore: person

#### Input : 

And here's to you, Mrs Robinson
Jesus loves you more than you will know

#### Output : 

Mrs Robinson : person
Jesus : person

#### Input : 

j'ai acheté une voiture a 13 000€

#### Output : 

13 000€ : price

#### Input : 

Bonjour monsieur Lafayette, j'ai bien reçu vôtre demande d'envoi de chéquier pour votre femme Marie, que je vous fait parvenir à votre domicile au 15 rue de la boetie, 75002 Paris. Bonne journée. Rémi.

#### Output : 

monsieur Lafayette : person
Marie : person
15 rue de la boetie, 75002 Paris : address
Rémi : person

## Sentiment + Why 

### TEST 

Chers responsables du service client,
Je vous écris pour exprimer ma grande déception concernant mon compte bancaire. Malheureusement, les frais supplémentaires imprévus et les erreurs répétées dans mes relevés m'ont laissé une impression d'incompétence et de négligence de votre part. J'attends de ma banque un service fiable et transparent, ce qui n'a malheureusement pas été le cas jusqu'à présent. J'espère que vous prendrez rapidement des mesures pour résoudre ces problèmes et regagner ma confiance en tant que client. Votre prompte action est vivement souhaitée.
Cordialement,

### TRAINING

#### Input : 

Chère équipe du service client,
Je vous écris aujourd'hui pour exprimer ma profonde insatisfaction à l'égard des services que j'ai reçus de votre banque. En tant que cliente fidèle depuis plusieurs années, je m'attendais à un niveau de service irréprochable, mais malheureusement, mon expérience récente a été extrêmement décevante.
Tout d'abord, laissez-moi vous expliquer la situation. J'ai récemment effectué une demande de prêt auprès de votre établissement afin de financer un projet qui me tient à cœur. J'ai fourni tous les documents requis et j'ai attendu avec impatience une réponse de votre part. Cependant, les délais annoncés n'ont pas été respectés et j'ai dû relancer à plusieurs reprises pour obtenir des informations sur l'avancement de mon dossier. Cette communication inadéquate a généré un grand stress et une perte de temps considérable de ma part.
De plus, lorsque j'ai enfin réussi à obtenir une réponse, j'ai été surprise de constater que ma demande de prêt avait été rejetée sans explication claire. Je me suis sentie complètement abandonnée et ignorée, d'autant plus que ma situation financière est solide et que je répondais à tous les critères requis.
En outre, j'ai rencontré des problèmes récurrents avec les services en ligne de votre banque. Les transactions en ligne sont souvent lentes et instables, ce qui rend difficile la gestion de mes comptes. De plus, le service d'assistance téléphonique que vous proposez est souvent surchargé, ce qui entraîne de longues attentes et une frustration accrue.
En tant que cliente, je m'attendais à être traitée avec respect et considération, ce qui n'a malheureusement pas été le cas. Je suis profondément déçue par l'attitude générale du personnel de votre banque et par le manque d'efforts déployés pour résoudre mes problèmes.
Je vous prie donc de bien vouloir prendre en considération mes préoccupations et de trouver une solution satisfaisante à mes problèmes. Je souhaiterais être informée des raisons précises du rejet de ma demande de prêt et que vous preniez des mesures pour améliorer votre service clientèle en ligne et téléphonique.
Si aucune action n'est entreprise pour remédier à ces problèmes, je me verrai dans l'obligation de rechercher les services d'une autre institution bancaire, ce que je préférerais éviter, étant donné ma fidélité passée à votre établissement.
Je vous remercie de l'attention que vous porterez à ma requête et j'espère sincèrement que vous prendrez les mesures nécessaires pour rectifier la situation.
Cordialement,

#### Output : 

sentiment : négatif; 
Pourquoi : prêt rejeté, mauvais service en ligne

#### Input : 

Chère équipe du service client,
J'espère que ce courriel vous trouve bien. Je me permets de vous contacter aujourd'hui pour clarifier une situation concernant mon compte bancaire.
En consultant mon relevé de compte récent, j'ai remarqué la présence d'un découvert dont je n'ai pas connaissance. Étant donné que je suis très attentif à mes finances personnelles et que je veille à maintenir mon compte en bon état, cette découverte m'a surpris.
Je souhaiterais obtenir des informations supplémentaires sur les raisons de ce découvert. J'aimerais comprendre les frais qui y sont associés et les circonstances qui ont conduit à cette situation. Il est important pour moi d'avoir une vision claire de mes transactions et de pouvoir résoudre ce problème de manière adéquate.
De plus, je vous serais reconnaissant de bien vouloir m'indiquer les démarches nécessaires pour régulariser cette situation de découvert. Je suis disposé à prendre les mesures appropriées pour rétablir un solde positif dans les plus brefs délais.
Dans l'attente de votre réponse, je vous remercie par avance pour votre attention et votre assistance dans la résolution de cette situation. J'apprécie votre approche professionnelle et j'ai confiance en votre capacité à trouver une solution satisfaisante.
Cordialement,

#### Output : 

sentiment : négatif;
Pourquoi : le client a un découvert sans raison particulière

#### Input : 

Chère équipe du service client,
Je tiens à prendre quelques instants pour exprimer ma satisfaction et ma gratitude envers votre banque. En tant que cliente depuis plusieurs années, je suis extrêmement satisfaite de la qualité des services que j'ai reçus de votre part. Votre professionnalisme, votre efficacité et votre souci du détail ont contribué à rendre mes interactions avec votre établissement exceptionnelles.
Tout d'abord, je souhaite souligner l'excellence de votre service client. Chaque fois que j'ai eu une question ou besoin d'assistance, votre équipe s'est montrée disponible, amicale et compétente. Les conseillers ont toujours pris le temps de m'écouter attentivement et de répondre à mes préoccupations de manière claire et détaillée.
De plus, vos services en ligne sont d'une grande convivialité et d'une fiabilité exemplaire. La plateforme facilite la gestion de mes comptes, les transactions sont rapides et sécurisées, ce qui me donne une grande tranquillité d'esprit.
En outre, j'apprécie énormément la diversité des produits et des services que vous proposez. Votre banque offre une gamme complète de solutions financières adaptées à mes besoins, ce qui me permet de gérer mes finances de manière optimale.
Enfin, je tiens à souligner l'engagement de votre banque envers la communauté. Vos initiatives sociales et environnementales témoignent d'une responsabilité sociétale que je trouve admirable.
En conclusion, je tenais à vous adresser mes sincères félicitations pour la qualité de votre service bancaire. Votre équipe a su instaurer une relation de confiance avec moi en offrant un niveau de service exceptionnel. Je recommanderai volontiers votre banque à mon entourage et je suis fière de faire partie de votre clientèle.
Je vous souhaite une excellente continuation et je vous remercie chaleureusement pour votre dévouement et votre professionnalisme.
Cordialement,

#### Output : 

sentiment : positif ;
Pourquoi : excellent service et bon service en ligne



## CHALLENGE

### TEST 

#### Input : 

Chers responsables du service client, 
Je vous écris pour exprimer ma grande déception concernant mon compte bancaire. Malheureusement, les frais supplémentaires imprévus et les erreurs répétées dans mes relevés m'ont laissé une impression d'incompétence et de négligence de votre part. J'attends de ma banque un service fiable et transparent, ce qui n'a malheureusement pas été le cas jusqu'à présent. J'espère que vous prendrez rapidement des mesures pour résoudre ces problèmes et regagner ma confiance en tant que client. Votre prompte action est vivement souhaitée. 
Cordialement,

Stéphanie DUPONT 
0633659864
