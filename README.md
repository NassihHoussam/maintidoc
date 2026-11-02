# MaintiDoc — Corpus de Maintenance Industrielle pour Assistant RAG

Projet de référence pour l'évaluation et le benchmark d'un assistant documentaire intelligent (RAG) appliqué à la maintenance industrielle.

## 📁 Structure du Répertoire

`	ext
maintidoc/
├── README.md                  # Documentation du projet
├── .gitignore                 # Fichiers exclus du versionnement
├── docs/
│   └── diagrammes/            # Diagrammes d'architecture et flux RAG
└── corpus/
    ├── inventaire.csv         # Inventaire détaillé des documents (20 colonnes)
    ├── prompts_corpus.md      # Registre des prompts de génération (P01 à P40)
    ├── documents/
    │   ├── famille_1/         # Pompes centrifuges industrielles (Cas 01 à 20)
    │   └── famille_2/         # Compresseurs d'air à vis (Cas 21 à 38, 40)
    └── images/                # Schémas et éléments visuels extraits
`

## ⚙️ Familles d'Équipements Couvertes

1. **Famille 1 — Pompes Centrifuges Industrielles** (amille_1) :
   - Identifiants cibles : POMPE-A-01 ; POMPE-B-01
   - Domaines : Électricité / alimentation, Surcharge, Hydraulique, Étanchéité mécanique, Paliers, Désalignement, Roue, Vannes, Clapets, Transitoires, etc.
   - 20 fiches techniques complètes (CAS 01 à CAS 20).

2. **Famille 2 — Compresseurs d'Air à Vis** (amille_2) :
   - Identifiants cibles : COMP-A-01 ; COMP-B-01
   - Domaines : Pneumatique, Refroidissement, Lubrification, Filtration, Sécurité, Séparation air-huile, Courroies, Régulation, Pressostats, etc.
   - 19 fiches techniques complètes (CAS 21 à CAS 38 et CAS 40).

## 📊 Inventaire et Métadonnées (inventaire.csv)

L'inventaire consigne l'ensemble des métadonnées requises pour chaque document :
- **Identification & Fichiers** : document_id, ichier, 	itre, amille_equipement, equipement_id, 	ype_document.
- **Caractéristiques techniques** : ersion, 
b_pages, langue, ormat, elements_visuels.
- **Origine & Traçabilité IA** : provenance, licence, genere_par_ia, outil_ia, erifie_par, corrections.
- **Gestion des accès & Rôles de test** : groupe_acces, usage_test (normal, ambigu, contradictoire), 
emarques.

## ✍️ Auteur

- **Houssam Nassih** — [GitHub Profil](https://github.com/NassihHoussam/maintidoc)
