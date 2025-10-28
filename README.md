## Lancement de l'application

### 1- Interface Graphique Complète
Vous pouvez lancer **l’interface graphique complète** qui regroupe toutes les fonctionnalités du TP2 :  
- Visualisation du graphe de couplage  
- Regroupement hiérarchique (dendrogramme)  
- Identification des modules  

**Fichier principal :** `tp2p1.CouplingGraphGUIFull.java`  
**Lancement :** depuis votre IDE ou via Maven/ligne de commande.  

---

### 2- Générateur de Graphe de Couplage
Pour générer uniquement le **graphe de couplage** :  
- Exécutez le générateur correspondant (`exercice1.CouplingGraphGenerator` ou `exercice1.SpoonCouplingGraphGenerator`)  
- Le fichier `.dot` est enregistré dans le **répertoire de sortie configuré** dans le code (modifiez-le selon vos besoins).  

---

### 3- Visualisation du Graphe
- Pour afficher le graphe généré, utilisez le **viewer associé** (`CouplingGraphViewer` ou `SpoonCouplingGraphViewer`)  
- L’image est générée automatiquement à partir du fichier `.dot`  

---

### 4- Regroupement Hiérarchique
- Exécutez `exercice2.HierarchicalClusteringVisualizer` ou `SpoonHierarchicalClustering`  
- Le **dendrogramme** s’affiche dans une nouvelle fenêtre  
- Vous pouvez ajuster les paramètres directement dans le code si nécessaire (ex. seuil de distance, chemins d’accès aux fichiers)  

---

### 5- Identification des Modules
- Utilisez `exercice2.ModuleIdentifier` ou `SpoonModuleIdentifier`  
- Les modules identifiés sont affichés dans la console 
- **Important :** adaptez les chemins vers les fichiers `.dot` ou dossiers source avant exécution  

---

## Remarques sur les chemins
- Tous les chemins de fichiers/dossiers (entrée et sortie) sont définis **dans le code source**  
- Modifiez-les selon votre organisation de projet avant de lancer les programmes  

---

## Résumé 
1. Lancer l’interface graphique complète pour tout le TP  
2. Ou exécuter séparément chaque composant : générateur, visualiseur, clustering, identification de modules  
3. Adapter les chemins de fichiers/dossiers selon vos besoins  

---
