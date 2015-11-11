# Générateur pour Cards Against Humanity
Ce script crée un jeu de cartes basé sur Cards Against Humanity à partir d'un fichier CSV.

* [Cards Against humanity](http://cardsagainsthumanity.com/) : Cards Against Humanity is a party game for horrible people. Unlike most of the party games you've played before, Cards Against Humanity is as despicable and awkward as you and your friends
* [Scribus](http://www.scribus.net) : a page layout program for Linux, FreeBSD, PC-BSD, NetBSD, OpenBSD, Solaris, OpenIndiana, Debian GNU/Hurd, Mac OS X, OS/2 Warp 4, eComStation, Haiku and Windows

## Utilisation ##
* Ouvrir le fichier Excel **cards\White Cards.xlsx** et mettre votre version anglaise et française des cartes blanches
* Enregistrer le fichier Excel au format CSV (**cards\White Cards.csv**) en utilisant le **point-virgule** (**;**) comme séparateur
* Ouvrir le fichier Excel **cards\Black Cards.xlsx** et mettre votre version anglaise et française des cartes noires
* Enregistrer le fichier Excel au format CSV (**cards\Black Cards.csv**) en utilisant le **point-virgule** (**;**) comme séparateur
* Lancer le script **CreateCard.py** depuis Scribus (Scripts->Execute Script)
* Saisir les infos du CSV 
    * Pour générer la version anglaise du jeux  : **;"0**
    * Pour générer la version française : **;"1**
* Sélectionner le fichier CSV à traiter
* Sélectionnere le type de carte à générer (blanche - **w**, ou noire - **b**)
* Dans Scribus, aller dans **File->Document Setup** et choisir le mode **A4 - Paysage / A4 - Landscape**
* Dans Scribus, aller dans **File->Export->Save as PDF...**
* Voilà!

## Réglements ##
[Réglements officiels du jeu original](http://s3.amazonaws.com/cah/CAH_Rules.pdf "Réglements officiels du jeu original")

## Disclaimer ###
*Cards Against Humanity est distribué sous une licence Creative Commons, pas d'utilisation commerciale sans l'autorisation de https://cardsagainsthumanity.com/*