# Dashboard Power BI — Projet Sarawak

Projet réalisé dans le cadre du cours de Clinique IA à **Aivancity**, en PGE 1.

---

## Le projet

On a travaillé avec **Sarawak**, une société qui développe des outils de suivi commercial terrain pour ses clients en grande distribution (comme Trip ou Duracell). L'idée de départ était de refaire leur dashboard de suivi des visites en points de vente (PDV), et d'en faire un **template réutilisable** pour n'importe quel client de Sarawak.

Le dashboard a été entièrement construit sous **Power BI Desktop** à partir de 8 tables de données réelles.

---

## Ce qu'on a construit

Le dashboard est composé de 3 pages :

**Couverture** — vue globale de l'activité terrain : combien de PDV ont été visités, à quelle fréquence, et comment les visites se répartissent dans le temps.

**DN (Distribution Numérique)** — suivi du référencement des produits dans les PDV : taux de DN par enseigne, facings, ruptures, et évolution semaine par semaine.

**Concurrence** — veille terrain : prix relevés par rayon, facings par rayon, et effort de veille par chef de secteur.

---

## Les données

8 tables ont été utilisées :

| Table | Contenu |
|-------|---------|
| Activité Productivité | Visites terrain |
| Astargets | Référentiel des PDV |
| DN | Distribution numérique par produit et PDV |
| DN semaines | Évolution hebdomadaire de la DN |
| Concurrence | Relevés concurrentiels |
| Visibilité | Présence en rayon |
| Plan Couv | Planification des visites |
| Contacts | Interlocuteurs en PDV |

---

## Le template

Une fois le dashboard finalisé, on l'a exporté en fichier `.pbit` (format template Power BI). L'idée c'est que Sarawak peut ouvrir ce fichier pour un nouveau client, connecter ses données, changer les couleurs, et le dashboard est prêt — sans tout reconstruire from scratch.

---

## Comment ouvrir le projet

1. Télécharger le fichier `dashboard_sarawak.pbix`
2. L'ouvrir avec Power BI Desktop
3. Pour le template : ouvrir `template_sarawak.pbit` et connecter sa propre source de données

---

## Équipe

- Tiornan Koné
- Yacin Omar
- Dieuveil Koumou
- Ryan Chigang

Présentation : **28 avril 2026**
Cours : Clinique IA — Aivancity PGE 1

