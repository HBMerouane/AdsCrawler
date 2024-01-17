# AdsCrawler
<table><tr><td>
New listings on classified advertisement websites that might interest us and that we would want to be the first to review, <i>AdsCrawling</i> tracks these ads and send alerts instantly. Supported websites: Ebay, KleinAnzeigen, Leboncoin.
*Python, Selenium*
</td></tr></table>

## Context
Souvent, on a cherche un produit ou un service sur les sites d'annonces mais on le trouve pas ou on arrive en retard, une autre personne l'a déjà pris. Ces sites comme Ebay, Leboncoin et la plupart des autres sites, offrent la possibilité de recevoir des alertes dès que notre recherche donne de nouveaux résultats. Le problème est que ces alertes sont limitées en nombre et arrivent souvent en retard. AdsCrawler est un script qui permet de surveiller les nouvelles annonces sur ces sites répondant à des critères prédéfinis sur le site ou configurés dans le script. L'utilisateur reçoit alors une alerte l'informant en temps pseudo réel de la nouveauté, par télégramme ou autre moyen configurable.

## Comment ça fonctionne
AdsCrawler ouvre la page de recherche du site à surveiller et extrait toutes les annonces.

ensuite il regarde les nouvelles annonces en se basant sur l'historique de sa surveillance. Il fait ensuite un filtrage et élémination des annonces non pertinantes en se basant sur des mots clés configurés. Il détermine également les annonces urgentes à voir en se basant sur des critères définis par l'utilisateur.
