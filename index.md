---
title: Whisky Ontology
layout: default
---

The Whiskey Ontology is an attempt to convert key concepts from the world of whiskey into a reliable linked data model. Initial progress will be presented at the 2019 IA Conference in Orlando, FL during poster night.

For more information on the project, including open issues and how to contribute visit the [project page](github.com/rdf-models/whiskey).

## Classes
### Age Statement
Age statement for the product as defined by the distiller. Typically presented on the label.

IRI
: https://rdf-models.github.io/whiskey#AgeStatement

Example
: 17 years

### Blended Irish Whisky
Whisky blended from two or more different Irish whisky types including pot stills, malt, or grain whisky

IRI
: https://rdf-models.github.io/whiskey#BlendedIrishWhisky

Superclass
: [Blended Whiskey](#blendedWhiskey)
: [Irish Whisky](#irishWhisky)

### Blended Scotch
A blend of two or more single grain Scotch whiskies with optional caramel coloring 

IRI
: https://rdf-models.github.io/whiskey#BlendedScotch

Superclass
: [Blended Whiskey](#blendedWhiskey)

### Blended Whiskey
Whiskey blended from multiple sources with the optional addition of neutral grain spirits, colorings, or other additives

IRI
: https://rdf-models.github.io/whiskey#BlendedWhiskey

Superclass
: [Whiskey](#whiskey)

Subclasses
: [Blended Irish Whisky](#blendedIrishWhisky)
: [Blended Scotch](#blendedScotch)

### Bourbon
Whiskey produced in the United States with a minimum grain bill of 51% then aged in new American oak

IRI
: https://rdf-models.github.io/whiskey#Bourbon

Superclass
: [Whiskey](#whiskey)

### Canadian Whisky
Whisky distilled in Canada then aged for a minimum of three years. Additional flavorings are allowed as is blending with corn spirits.

IRI
: https://rdf-models.github.io/whiskey#CanadianWhisky

Superclass
: [Whiskey](#whiskey)

Subclass
: [Straight Canadian Whisky](#straightCanadianWhisky)

### Corn Whiskey
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#CornWhiskey

Superclass
: [Straight Whiskey](#straightWhiskey)

### Country
Country where whiskey was distilled and bottled.

IRI
: https://rdf-models.github.io/whiskey#Country

Subclass
: [Subdivision](#subdivision)

Example
: Australia
: United States

### Distiller
Corporate entity which distilled the whiskey. 

IRI
: https://rdf-models.github.io/whiskey#Distiller

Example
: Buffalo Trace
: Amrut

### Finishing Cask
Secondary cask type(s) in which the whiskey was finished after distillation

IRI
: https://rdf-models.github.io/whiskey#FinishingCask

Example
: Calvados
: Port

### Flavored Whiskey
Whiskey to which additional flavors have been added such as cinnamon, honey, or cherries

IRI
: https://rdf-models.github.io/whiskey#FlavoredWhiskey

Superclass
: [Whiskey](#whiskey)

### Irish Whisky
Whisky distilled in the Republic of Ireland then aged for a minimum of three years

IRI
: https://rdf-models.github.io/whiskey#IrishWhisky

Superclass
: [Whiskey](#whiskey)
: [Single Malt](#singleMalt)

Subclasses
: [Blended Irish Whisky](#blendedIrishWhisky)
: [Single Malt Irish](#singleMaltIrish)

### Japanese Whiskey
Whiskey produced in Japan which most often resembles either Lowland or Speyside style Scotch

IRI
: https://rdf-models.github.io/whiskey#JapaneseWhiskey

Superclass
: [Whiskey](#whiskey)

### Japanese Single Malt
__Description needed__

IRI
: https://rdf-model.github.io/whiskey#JapaneseSingleMalt

Superclasses
: [Japanese Whisky](#japaneseWhiskey)
: [Single Malt](#singleMalt)

### Maryland Rye
Rectified rye whisky using flavoring agents such as prune juice, cherry juice, caramel coloring and other ingredients

IRI
: https://rdf-models.github.io/whiskey#MarylandRye

Superclass
: [Rye Whiskey](#ryeWhiskey)

### Region
Region within Scotland where the whisky was distilled and produced

IRI
: https://rdf-models.github.io/whisky#Region

Superclass
: [Country](#country)

Subclass
: [Subregion](#subregion)

### Rye Whiskey
Whiskey produced with a minimum of 51% rye mash bill and aged in new American white oak for at least two years

IRI
: https://rdf-models.github.io/whiskey#RyeWhiskey

Superclass
: [Whiskey](#whiskey)

Subclasses
: [Maryland Rye](#marylandRye)
: [Straight Rye](#straightRye)

### Scotch
Whisky produced in Scotland most often using malted barley and aged for a minimum of three years in oak barrels

IRI
: https://rdf-models.github.io/whiskey#Scotch

Superclass
: [Whiskey](#whiskey)

Subclasses
: [Blended Scotch](#blendedScotch)
: [Scottish Grain Whisky](#scottishGrainWhisky)
: [Single Malt Scotch](#singleMaltScotch)
: [Vatted Malt Scotch](#vattedMaltScotch)

### Scottish Grain Whiskey
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#ScottishGrainWhiskey

Superclass
: [Scotch](#scotch)

### Series
Brand, collection, or seres to which the whiskey belongs as defined by the distiller, independent bottler, or holding company

IRI
: https://rdf-models.github.io/whiskey#Series

Example
: Antique Collection
: Eagle Rare
: Single Malt Collection

### Single Malt
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#SingleMalt

Superclass
: [Whiskey](#whiskey)

Subclasses
: [Japanese Single Malt](#japaneseSingleMalt)
: [Single Malt Irish](#singleMaltIrish)
: [Single Malt Scotch](#singleMaltScotch)

### Single Malt Irish
Irish whisky distilled and aged at a single location for a minimum of three year using only malted barley

IRI
: https://rdf-models.github.io/whiskey#SingleMaltIrish

Superclass
: [Irish Whisky](#irishWhisky)
: [Single Malt](#singleMalt)

### Single Malt Scotch
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#SingleMaltScotch

Superclasses
: [Scotch](#scotch)
: [Single Malt](#singleMalt)

### Straight Bourbon
Bourbon which has been aged for a minimum of two year in new American oak barrels

IRI
: https://rdf-models.github.io/whiskey#StraightBourbon

Superclass
: [Bourbon](#bourbon)
: [Straight Whiskey](#straightWhiskey)

### Straight Canadian Whisky
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#StraightCanadianWhisky

Superclasses
: [Canadian Whisky](#canadianWhisky)
: [Straight Whiskey](#straightWhiskey)

### Straight Rye
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#StraightRye

Superclasses
: [Rye Whiskey](#ryeWhiskey)
: [Straight Whiskey](#straightWhiskey)

### Straight Whiskey
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#StraightWhiskey

Superclass
: [Whiskey](#whiskey)

Subclasses
: [Corn Whiskey](#cornWhiskey)
: [Tennessee Whiskey](#tennesseeWhiskey)
: [Wheat Whiskey](#wheatWhiskey)
: [White Whiskey](#whiteWhiskey)

### Subdivision
A secondary administrative region within a country such as a state (United States), county (England), or province (Canada)

IRI
: https://rdf-models.github.io/whiskey#Subdivision

Example
: Kentucky
: Tennessee

### Subregion
A secondary region within Scotland where whisky is produced

IRI
: https://rdf-models.github.io/whiskey#Subregion

Superclass
: [Region](#region)

Example
: Arran
: Jura

### Tennessee Whiskey
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#TennesseeWhiskey

Superclass
: [Straight Whiskey](#straightWhiskey)

### Vatted Malt Scotch
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#VattedMaltScotch

Superclass
: [Scotch](#scotch)

### Wheat Whiskey
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#WheatWhiskey

Superclass
: [Straight Whiskey](#straightWhiskey)

### Whiskey
A spirit distilled from malted grains and typically aged in wooden casks. The high level class for all whisk(e)y styles.

IRI
: https://rdf-models.github.io/whiskey#Whiskey

Subclasses
: [Blended Whiskey](#blendedWhiskey)
: [Bourbon](#bourbon)
: [Canadian Whiskey](#canadianWhisky)
: [Flavored Whiskey](#flavoredWhiskey)
: [Irish Whiskey](#irishWhisky)
: [Japanese Whiskey](#japaneseWhiskey)
: [Rye Whiskey](#ryeWhiskey)
: [Scotch](#scotch)
: [Single Malt Whiskey](#singleMaltWhiskey)
: [Straight Whiskey](#straightWhiskey)

### White Whiskey
__Description needed__

IRI
: https://rdf-models.github.io/whiskey#WhiteWhiskey

Superclass
: [Straight Whiskey](#straightWhiskey)

## Properties
### abv
### finishedIn
### hasAgeStatement
### isPartOfSeries
### isProducedBy
### produces
### fromSingleCask
### bottledInBond
### inProduction

