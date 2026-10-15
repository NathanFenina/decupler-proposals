---
name: decupler-proposition
description: Construit une proposition commerciale Décupler (page HTML publiée en artifact) à partir d'un audit SEO/GEO, des notes de Nathan et du transcript d'appel (Fireflies). Déclencher sur "proposition", "propale", "offre", "formules", "pricing", "devis d'accompagnement", "préparer la proposition pour <client>", ou quand l'utilisateur colle un lien d'audit + un transcript en demandant de préparer la suite. Couvre la structure persuasive, le chiffrage (volume d'actions, rythme, projection 12 mois), les 3 formules, l'engagement, le design et les règles de prix (dont fixe + variable pour les artisans BTP).
---

# Proposition commerciale Décupler

Référence réelle : `naturedea-proposition/index.html` (Natur'édéa, oct. 2026). Repartir de ce fichier plutôt que de zéro.

## Entrées à réunir
1. **L'audit** du client (artifact claude.ai → `Artifact read`) : trafic, mots-clés, zone de bascule, concurrent benchmark, citations IA, leviers, scénarios 12 mois. Ne réutiliser que des chiffres mesurés.
2. **Le transcript d'appel** : en extraire 3-5 phrases verbatim du prospect (douleurs, frustrations avec le prestataire actuel, définition de la réussite, budget actuel). Elles portent la partie émotion.
3. **Le prix payé aujourd'hui** et ce qu'il achète (nb de contenus, intégration ou non) : sert d'ancre de comparaison.

## Principes
- **Casser le pattern** dès le titre : pas de « Proposition SEO » générique. Une phrase chiffrée qui recadre le problème (ex. « Pour que le SEO vende, il faut 151 pages et 8 chantiers. La question, c'est à quel rythme. »).
- **Convaincre par l'émotion ET par les maths** : les mots du prospect d'un côté, le calcul de l'autre.
- **Focus résultat business** : leads (appels, demandes) pour du B2B/local, ventes/commandes pour l'e-commerce. Le SEO n'est qu'un moyen.
- **Pragmatique** : montrer concrètement ce qu'on fait pour atteindre le résultat, pas une liste de services.
- **Honnêteté** : toute hypothèse (panier moyen, conversion, valeur d'un lead) est marquée « exemple, à remplacer par vos chiffres ». Jamais de chiffre inventé présenté comme mesuré. Objectif ≠ promesse.

## Structure de la page (dans cet ordre)
1. **Hero** : titre qui casse le pattern + citation du prospect + 4 chiffres clés (déclin, absence IA, écart concurrent).
2. **Le problème vu par lui** : ses phrases du call, chacune reliée à un constat de l'audit, puis sa définition de la réussite.
3. **Trois chemins — seul on se perd, ensemble on arrive** : faire seul / continuer comme aujourd'hui / avec Décupler, avec le résultat chiffré à 12 mois de chacun (prolonger la pente actuelle pour les deux premiers).
4. **Situation rêvée** : « un lundi matin dans 12 mois », 5-6 résultats concrets.
5. **Concurrents on-page / off-page** : tableau d'écarts (×N) avec le concurrent benchmark, puis deux colonnes « ce qu'ils publient » / « où l'on parle d'eux », logos des marques citées par les IA.
6. **Volume d'actions nécessaire** : le chantier compté ligne par ligne (pages par type + chantiers techniques + actions off-page). Montrer **beaucoup** de volume (toute la gamme, toutes les grappes, articles à remettre à niveau) — l'ampleur justifie le prix. Puis **« à ce rythme, combien de mois »** : barres comparant le rythme actuel et chaque formule, + barres liens/autorité sur 12 mois.
7. **Projection à 12 mois** : courbe des 3 scénarios + pente actuelle, et un **calculateur** interactif (panier/valeur du lead, conversion, réachat) → leads ou CA, ROI année 1, point mort, équivalent Google Ads, année 2.
8. **Stratégie globale — les tiroirs** : les canaux à ouvrir (technique, entité IA, fiches/pages qui convertissent, contenus de grappe, classements & annuaires, liens/presse/avis) avec la formule qui ouvre chaque tiroir. Puis la **roadmap** 4 trimestres.
9. **3 formules** (voir pricing).
10. **Engagement** (tableau).
11. **Cadeaux, bonus, FOMO** : cadeaux déjà prêts (livrables de l'audit mis en ligne semaine 1), bonus daté avec compte à rebours, exclusivité sectorielle si vraie.
12. **Démarrer** : chronologie du 2e rendez-vous au bilan du mois 1 ; CTA **lien Stripe pour valider le premier mois avant tout contrat** (demander le lien à Nathan ; à défaut, Calendly `https://calendly.com/fenina-nathan/consultationstrategique` et le signaler).
13. **Confiance** : logos clients (style Canva / Scalezia : vrais logos en data URI), cas similaires uniquement s'ils sont réels, carte auteur Nathan.

## Pricing
- **3 formules**, celle du milieu marquée « Recommandée ». Pour une PME/e-commerce : fourchette ~800 → 2 000 € HT/mois (Natur'édéa : 890 / 1 490 / 1 990). Idéalement viser des accompagnements à 2-3 K€ quand le prospect le permet.
- **Vendre des livrables, pas des jours** : afficher des pages par mois (ex. 8 / 16 / « plus de 16 »), jamais un équivalent en jours (évite la comparaison au TJM de l'agence en place).
- **Coût par page vs aujourd'hui** : calculer prix ÷ pages et le comparer à ce que le prospect paie déjà par contenu non intégré. Argument le plus fort.
- **Formule haute** : ne pas donner son nombre de pages (« encore plus »), elle se distingue par le **netlinking**, dont des **achats de liens inclus** (sites validés avec le client). Surveiller la marge : liens santé ≈ 100-250 € pièce ; si besoin préciser un plafond de budget d'achat inclus.
- **Engagement** : 12 mois minimum (le mois 1 payé via Stripe compte dedans). Tableau en trois lignes pour ancrer le 12 mois :
  - sans engagement : frais de mise en place élevés (≈ 3 500 €, bien au-dessus d'un mois de formule) ;
  - 12 mois : mise en place offerte ;
  - 24 mois : mise en place offerte + −10 %.
  En négociation, céder sur la mise en place, **pas** sur le prix mensuel.
- **Fixe + variable** (pour ceux qui négocient, et en cold mail artisans BTP — ex. Dovan, Millet, Roger, New Lead BTP) :
  1. fixe 1 000 à 1 500 €/mois sur 12 mois ;
  2. fixe 500 €/mois + un montant par lead (appel) généré, suivi par numéro de tracking.
  Dans ce cas la projection et le calculateur raisonnent en appels/leads par mois.

## Design
- Charte decupler.com, **version claire uniquement** (pas de mode sombre) : fond `#F8FAFC`, cartes blanches, bordures `#E2E8F0`, texte `#0F172A`/`#475569`, accent violet `#6D4AE8`, dégradé `linear-gradient(135deg,#6366F1,#8B5CF6)` sur boutons, mots clés du titre et marque. Titres **Syne** 700, texte **DM Sans**, chiffres en mono tabulaires.
- Logos concurrents/clients en data URI (pas d'image externe : la CSP de l'artifact les bloque). Photo de Nathan : `assets/nathan.png` réduite en JPEG 160 px.
- Vérifier à 400 px de large (pas de scroll horizontal) avant de publier.

## Livraison
- Fichier : `<client>-proposition/index.html` dans ce repo, commit + push sur la branche de travail, puis publication via l'outil Artifact (rappeler que l'artifact est privé tant que Nathan ne le partage pas).
- Lister en fin de réponse ce qui reste à confirmer par Nathan : lien Stripe, date limite du bonus, exclusivité, hypothèses du calculateur, logos.
