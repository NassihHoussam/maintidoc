# Registre des Prompts de Génération du Corpus MaintiDoc

Ce document consigne les prompts d'ingénierie utilisés avec ChatGPT pour générer les fiches de cas de maintenance synthétiques du corpus.

---

## Modèle de Prompt Général (P01 à P40)

**Rôle Système :**
> Vous êtes un ingénieur expert en maintenance industrielle (spécialisé en pompes centrifuges et compresseurs d'air à vis industriels). 
> Générez une fiche technique d'intervention structurée, réaliste et pédagogique pour un cas d'incident ou de défaillance.

**Prompt Utilisateur Template :**
> Rédigez le cas de maintenance suivant :
> - Numéro du cas : {CAS_NUM} / 40
> - Équipement : {EQUIPEMENT}
> - Titre du cas : {TITRE}
> - Domaine : {DOMAINE}
> - Niveau de criticité : {CRITICITE}
>
> La fiche doit impérativement comporter les sections suivantes :
> 1. Symptômes observés
> 2. Contexte du cas
> 3. Constats de diagnostic
> 4. Cause probable — à confirmer
> 5. Action corrective recommandée
> 6. Vérification après intervention
> 7. Prévention / suivi
> 8. Avertissement sécurité et limites (consignation, EPI, habilitations).

---

## Index des Prompts par Document

- **P01 à P20** : Fiches Famille 1 (Pompes Centrifuges Industrielles)
  - P01 : La pompe ne démarre pas — absence d’alimentation
  - P02 : Déclenchement répété du relais thermique
  - P03 : Débit insuffisant — crépine ou filtre colmaté
  - P04 : Vibrations et bruit de graviers — suspicion de cavitation
  - P05 : Perte d’amorçage après arrêt
  - P06 : Fuite de garniture mécanique
  - P07 : Surchauffe des paliers
  - P08 : Accouplement désaligné
  - P09 : Roue déséquilibrée ou endommagée
  - P10 : Vanne d’aspiration partiellement fermée
  - P11 : Vanne de refoulement fermée ou trop étranglée
  - P12 : Clapet anti-retour qui ne ferme plus
  - P13 : Fuite sur bride ou joint de tuyauterie
  - P14 : Fonctionnement hors courbe — débit trop faible
  - P15 : Fuite d’huile du palier
  - P16 : Moteur qui chauffe anormalement
  - P17 : Corrosion ou érosion du corps de pompe
  - P18 : Bruit de roulement — roulement dégradé
  - P19 : Pulsations de débit et coups de bélier
  - P20 : Perte de performance après maintenance *(cas d'évaluation ambigu)*

- **P21 à P40** : Fiches Famille 2 (Compresseurs d'Air à Vis)
  - P21 : Pression d’air trop faible
  - P22 : Température de sortie d’air élevée
  - P23 : Consommation d’huile anormale
  - P24 : Filtre d’admission colmaté
  - P25 : Arrêts intempestifs — défaut de sécurité
  - P26 : Fuite d’air comprimé sur raccord
  - P27 : Séparateur air-huile saturé
  - P28 : Niveau d’huile trop bas
  - P29 : Huile dégradée ou contaminée
  - P30 : Courroie détendue ou usée
  - P31 : Vibrations anormales *(cas d'évaluation ambigu)*
  - P32 : Clapet de sortie fuyard
  - P33 : Électrovanne de charge/délestage bloquée
  - P34 : Moteur électrique en surcharge
  - P35 : Refroidisseur air-huile encrassé
  - P36 : Condensats mal évacués
  - P37 : Pressostat ou capteur de pression incohérent
  - P38 : Démarrages trop fréquents
  - P40 : Remise en service après maintenance incorrecte *(cas d'évaluation contradictoire)*
