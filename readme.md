# Archives statiques des sites Web de la 27e région

La 27e Région produit des sites Web, qui doivent être archivés en statique quand ils ne sont plus en usage. Ce référentiel fournit la méthodologie et l'état des lieux des sites.
Les archives sont envoyées sur Netlify pour relecture.

## Méthodologie

```bash
wget \
 --recursive \
 --no-clobber \
 --page-requisites \
 --html-extension \
 --convert-links \
 --restrict-file-names=windows \
 --domains nouveauxaccords.la27eregion.fr \
 --no-parent \
 nouveauxaccords.la27eregion.fr
```

## Archivés

### Capacités publiques
https://capacitespubliques.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains capacitespubliques.la27eregion.fr --no-parent capacitespubliques.la27eregion.fr
```

https://27eregion-capacitespubliques.netlify.app

### Nouveaux accords
https://nouveauxaccords.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains nouveauxaccords.la27eregion.fr --no-parent nouveauxaccords.la27eregion.fr
```

https://27eregion-nouveauxaccords.netlify.app

### Aménagement participatif
https://amenagementparticipatif.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains amenagementparticipatif.fr --no-parent amenagementparticipatif.fr
```

https://27eregion-amenagementparticipatif.netlify.app

### Labonautes 
https://labonautes.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains labonautes.fr --no-parent labonautes.fr
```

### Les Labonautes (le blog) 
https://leslabonautes.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains leslabonautes.la27eregion.fr --no-parent leslabonautes.la27eregion.fr
```

https://27eregion-leslabonautes.netlify.app

### Lieux Communs 
https://lieuxcommuns.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains lieuxcommuns.la27eregion.fr --no-parent lieuxcommuns.la27eregion.fr
```

### Déformation(s) 
https://deformations.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains deformations.la27eregion.fr --no-parent deformations.la27eregion.fr
```

### Enacting the commons 
https://enactingthecommons.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains enactingthecommons.la27eregion.fr --no-parent enactingthecommons.la27eregion.fr
```

### La Transfo : blogs 
https://latransfo.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains latransfo.la27eregion.fr --no-parent latransfo.la27eregion.fr
```

### Hopital
https://hopitalmetropole.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains hopitalmetropole.la27eregion.fr --no-parent hopitalmetropole.la27eregion.fr
```

### Repenser l’accueil en mairie
https://mairie19.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains mairie19.la27eregion.fr --no-parent mairie19.la27eregion.fr
```

### Gare de Montfort
https://garebzh.la27eregion.fr

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains garebzh.la27eregion.fr --no-parent garebzh.la27eregion.fr
```

https://27eregion-garebzh.netlify.app

### Territoire en résidences 
https://territoiresenresidences.wordpress.com

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains territoiresenresidences.wordpress.com --no-parent territoiresenresidences.wordpress.com
```

### Blog résidence à Cluny
https://residence27sgmap.wordpress.com

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains residence27sgmap.wordpress.com --no-parent residence27sgmap.wordpress.com
```

https://27eregion-residence27sgmap.netlify.app

### La Transfo : site final
https://transfocodesource.la27eregion.fr/index.html 
Ø	Attention, le site https://transfocodesource.la27eregion.fr renvoie une erreur 

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains transfocodesource.la27eregion.fr --no-parent transfocodesource.la27eregion.fr/index.html
```

https://27eregion-transfocodesource.netlify.app

## Cas particulier

### Admeen
https://readymag.website/u26414578/1158603/ 

```bash
wget --recursive --no-clobber --page-requisites --html-extension --convert-links --restrict-file-names=windows --domains readymag.website/u26414578/1158603/ readymag.website/u26414578/1158603/
```

## Encore en cours

### Rebonds

https://rebonds.la27eregion.fr

### Tronc Commun

https://tronc-commun.la27eregion.fr

### Nouvelles Mesures 
https://marvelous-swordfish-ba4.notion.site/Bienvenue-sur-le-carnet-de-bord-de-Nouvelles-Mesures-97d592b5a703492dba075ecc335837a6?pvs=74 
Ø	Carnet de bord sur notion 
