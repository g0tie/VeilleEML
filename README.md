# VeilleEML

## Partie simplifiée
L'EML est un format de fichiers utilisé par les logiciels de messagerie électroniques ou clients web (MS Outlook, Mozilla Thundebird, Gmail, etc...).
C'est un fichier de type texte qui contient l'en-tête, le sujet, le corps du mail. 
Il peut également contenir des liens hypertextes et des pièces jointes.

## Partie technique

Le format EML permet et standardisé.  Le stockage des mails sur le disque dur pour une consultation hors ligne ou pour le sauvegarder.
Etant donné le format type texte brut des fichiers, ils peuvent être ouvert avec n'importe quel éditeur de code.
Il y a un seul email par fichier EML.
L'entête contient beaucoup d'informataions comme: 
* la date 
* la provenance du mail (adresse ip, mail, id , date, heure)
* le destinataire
* le sujet
* l'ID du message (qui est unique)
* le type de fichier
* La signature DKIM (pemettant d'authentifier qu'un mail a bien été envoyé et est autorisé par le domaine)
* Le MIME version (pour les texte qui recquiert des caractères autres que ASCII)
* le MIME type (le type de fichier encodé exemple text/plain)

Le coprs du mail peut être au format HTML. La base 64 est utilisée pour encoder certains éléments (pièces jointes par exemple).

Exemple de fichier EML:

![image](https://user-images.githubusercontent.com/56622131/145756689-dcdfd0de-7ba0-4031-99a3-080f17e8e52c.png)
