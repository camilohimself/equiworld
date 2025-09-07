# CLAUDE.md - Documentation du Projet EquiWorld

## Contexte du Projet

**Client**: Jessy Putallaz et Marine Deléchat (couple, co-fondateurs)
**Projet**: EquiWorld - Écosystème digital pour révolutionner le monde équestre
**Phase actuelle**: Optimisation du Business Plan pour levée de fonds
**Budget proposé**: 2'100 CHF pour la phase d'optimisation complète
**Date**: Septembre 2025

## Vue d'Ensemble du Projet EquiWorld

### Vision
EquiWorld est un écosystème digital unique pensé pour révolutionner le monde équestre. L'ambition est de connecter les passionnés, les professionnels et les prestataires via une plateforme centrale moderne, intuitive et 100% dédiée à l'univers du cheval.

### Les 5 Plateformes Complémentaires (Mise à jour Sept. 2025)

#### 1. Equi Book (Nouveau nom - Annuaire)
- **Description**: "Google du monde équestre suisse" - Annuaire interactif des professionnels
- **Fonctionnalités**:
  - Référencement des professionnels (maréchaux, vétérinaires, ostéopathes, pensions, enseignants, selliers)
  - Module événementiel pour organisateurs (recherche prestataires, sponsors, bénévoles)
  - Système de mise en relation B2B
  - Visibilité pour sponsors potentiels

#### 2. Equi Deal (Marketplace pure)
- **Description**: Marketplace dédiée à la vente de chevaux et matériel
- **Fonctionnalités validées par questionnaire**:
  - Publication d'annonces avec géolocalisation
  - **Label EquiWorld** : Certification des prix par experts (USP majeur)
  - Durée moyenne de vente : 3-9 mois (insight pour le modèle économique)
  - Modération manuelle pour garantir la qualité

#### 2. Equi Job
- **Description**: Plateforme de mise en relation pour personnel temporaire
- **Fonctionnalités**:
  - Profils : palefreniers, soigneurs, grooms, chauffeurs, cavaliers professionnels
  - Certification après entretien vidéo obligatoire
  - Offres filtrées, validées et géolocalisées
  - Cotisation annuelle pour accès aux missions

#### 3. Equi Drive
- **Description**: Service de location de véhicules pour transport de chevaux entre particuliers
- **Fonctionnalités**:
  - Documents d'assurance intégrés
  - Système de réservation intégré
  - Géolocalisation des véhicules disponibles

#### 4. Equi Invest
- **Description**: Plateforme d'investissement participatif dans des chevaux de saut d'obstacles
- **Fonctionnalités**:
  - Investissement dès CHF 50.- (initialement 100.-)
  - Suivi quotidien (vidéos, nouvelles)
  - Assurance obligatoire des chevaux
  - Modèle juridique : Sàrl avec contrat de participation (évite la LPCC)
  - Répartition plus-value : 70% investisseurs, 20% cavalier, 10% plateforme
  - Commission plateforme : 10% montant initial + 5% sur plus-value

## Informations Financières Clés

### Levée de Fonds Recherchée
- **Montant total**: CHF 1'000'000.- pour 40% du capital
- **Valorisation actuelle**: CHF 2'500'000.-

### Répartition du Million CHF
- CHF 160'000 → Développement plateforme + création société
- CHF 60'000 → Frais fonctionnement informaticiens (2027-2028)
- CHF 180'000 → Rémunération personnes clés (CHF 60'000/an)
- CHF 600'000 → Marketing digital & communication, sponsoring (CHF 200'000/an)

### Timeline du Projet Original
- Phase 1 : 2025 (année en cours)
- Phase 2 : 2026-2027
- Phase 3 : 2027-2030
- Objectif 5 ans : Devenir la référence digitale équestre en Suisse, puis expansion européenne

## Points d'Amélioration Identifiés pour le Business Plan

### 1. Parcours des Fondateurs
- [ ] Détailler l'expérience de Jessy (cavalier professionnel)
- [ ] Préciser le rôle et l'expertise de Marine (responsable de structures)
- [ ] Renforcer la crédibilité de l'équipe fondatrice
- [ ] Ajouter leurs réalisations concrètes dans le monde équestre

### 2. Projections Financières
- [ ] Affiner les projections existantes avec hypothèses détaillées
- [ ] Assurer la cohérence et le réalisme des chiffres
- [ ] Détailler le break-even point
- [ ] Préciser les revenus par plateforme

### 3. Marketing Opérationnel
- [ ] Détailler la stratégie d'acquisition clients
- [ ] Plan SEO/SEA spécifique au secteur équestre
- [ ] Stratégie de partenariats (centres équestres, fédérations)
- [ ] KPIs et métriques de succès

### 4. Étude de Marché et Analyse Concurrentielle
- [ ] Taille du marché équestre suisse (CHF 300M mentionnés)
- [ ] Analyse concurrentielle détaillée
- [ ] Positionnement unique d'EquiWorld
- [ ] Barrières à l'entrée

### 5. Aspects Réglementaires (CRITIQUE)
- [ ] Clarifier la conformité FINMA pour EquiInvest
- [ ] Détailler le montage juridique évitant la LPCC
- [ ] Requirements KYC/AML
- [ ] Cadre légal pour les 4 plateformes

## Recommandations Stratégiques

### Pour le Business Plan
1. **Ajouter une section "Traction"**
   - LOI de cavaliers intéressés
   - Partenariats pré-signés
   - Liste d'attente utilisateurs

2. **Renforcer l'analyse concurrentielle**
   - Positionnement vs Ricardo, Anibis
   - Différenciation claire
   - Stratégie de défense

3. **Timeline plus agressive**
   - MVP en 6 mois au lieu de 12
   - Revenue dès le mois 7
   - Break-even année 2

4. **Section "Risques et Mitigation"**
   - Risque réglementaire FINMA
   - Risque adoption marché
   - Risque technique

### Pour le Développement Technique
1. **Architecture proposée**
   - SSO unifié pour les 4 plateformes
   - API Gateway + microservices
   - Infrastructure cloud scalable (AWS)
   - Stripe Connect pour les paiements complexes

2. **Priorisation des modules**
   - Phase 1: EquiDeal + préparation EquiInvest
   - Phase 2: EquiInvest complet
   - Phase 3: EquiDrive + EquiJob

## Livrables Attendus

1. **Business Plan optimisé** incluant :
   - Recherche approfondie sur le marché équestre
   - Réécriture stratégique orientée investisseurs
   - Mise en forme visuelle professionnelle
   - Executive summary percutant
   - Pitch deck de 15 slides

## Structure du Projet

```
EQUIWORLD/
├── CLAUDE.md (ce fichier)
├── business-plan/
│   ├── version-actuelle/
│   ├── version-optimisee/
│   ├── recherche/
│   └── templates/
├── documents/
│   ├── marketing/
│   ├── financier/
│   ├── juridique/
│   └── technique/
├── Documents/ (fichiers existants du client)
│   └── Projet Equi World (2)/
└── [fichiers racine]
```

## Notes de Travail Importantes

### Points Critiques à Surveiller
- **Complexité EquiInvest**: Fintech avec réglementation FINMA, pas une simple marketplace
- **Budget développement**: Client prévoit 160K CHF, évaluer si réaliste
- **Ressources opérationnelles**: Qui va gérer la modération, les RDV visio, le support ?
- **Acquisition clients**: Marché équestre traditionnel et fermé

### Questions Clés Non Résolues
1. Validation du modèle EquiInvest avec la FINMA ?
2. Pipeline de cavaliers prêts à proposer leurs chevaux ?
3. Stratégie d'acquisition des 1000 premiers utilisateurs ?
4. Équipe opérationnelle post-lancement ?

## Prochaines Étapes

1. ✅ Analyser le business plan existant
2. ✅ Explorer les ressources disponibles
3. ✅ Créer la structure de dossiers
4. ⏳ Évaluer précisément les sections à optimiser
5. ⏳ Préparer le plan d'action détaillé d'optimisation
6. ⏳ Commencer la rédaction des sections prioritaires
7. ⏳ Créer le pitch deck investisseurs
8. ⏳ Finaliser et livrer le business plan optimisé

## Contacts et Références

- **Client**: Jessy Putallaz (jessy@equiworld.ch - à confirmer)
- **Co-fondatrice**: Marine Deléchat
- **Notre proposition**: CHF 2'100 pour l'optimisation complète
- **Deadline**: À définir avec le client

---

*Document mis à jour le 06/09/2025 - Version 2.0*