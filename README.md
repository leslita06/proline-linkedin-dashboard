# Proline Logistics · Tableau de bord LinkedIn

Page en ligne : https://leslita06.github.io/proline-linkedin-dashboard/

## Mettre à jour les chiffres

Tout se modifie dans `data/donnees.json` ; la page se recalcule seule.

- `reel: true` : chiffre relevé et vérifiable. `reel: false` : exemple, affiché grisé avec la mention « exemple ».
- Quand un post est publié : passer son `statut` à `publie`, coller l'adresse du post dans `lien` et le nombre de réactions dans `reactions`.
- Chaque semaine : ajouter le relevé d'abonnés dans `semaines` et passer `abonnes_reel` à `true`.
- Quand l'accès administrateur de la page est donné : `acces_administrateur: true` masque le bandeau d'avertissement.

Chiffres réels au 02/11/2026 : abonnés (3 517 le 28/10, 3 519 le 02/11), aucune publication relevée sur 6 mois, calendrier de novembre (12 posts), concurrents relevés le 28/10/2026, objectifs à 30 jours.
