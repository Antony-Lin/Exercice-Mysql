# Exercice-Mysql

Exercice 1 :

SELECT * FROM `film` WHERE `date_sortie` > '1960'

SELECT `titre` FROM `film` WHERE `date_sortie` < '1960'

Exercice 2 : 

UPDATE `film` SET `description` = 'je suis le codeur' WHERE id = 35

Exercice 3 :
INSERT INTO `film`(`titre`,`slug`,`image`,`prix`,`description`,`date_sortie`) VALUES ('invasion-des-chien', 'chien', '1345674653413.png', '500', 'une vie rapide', '1940-11-11')

Exercice 5 :

DELETE FROM `film` WHERE `slug` > 't'
