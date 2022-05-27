

Objektkatalog des Paketes UML\_DM\_GA25\_Profiles\_V1
A {text-decoration: none }TD{border-bottom: solid black; border-bottom-width: 1px}


# Inhalt


[1 UML\_DM\_GA25\_Profiles\_V1](#1_UML_DM_GA25_Profiles_V1)


[1.1 Pakete](#1.1_Packages)


[2 DM\_GA25\_Profiles\_V1.ili](#2_DM_GA25_Profiles_V1.ili)


[2.1 Pakete](#2.1_Packages)


[3 GA25\_ProfilesCatalogues\_V1.ili](#3_GA25_ProfilesCatalogues_V1.ili)


[3.1 Pakete](#3.1_Packages)


[4 DM\_GA25\_Profiles\_V1](#4_DM_GA25_Profiles_V1)


[4.1 Pakete](#4.1_Packages)


[4.2 Klassen](#4.2)


[4.3 LineStructure](#4.3_LineStructure)


[4.4 MultiLine](#4.4_MultiLine)


[5 GA25\_ProfilesCatalogues\_V1](#5_GA25_ProfilesCatalogues_V1)


[5.1 Pakete](#5.1_Packages)


[6 Profiles](#6_Profiles)


[6.1 Klassen](#6.1)


[6.2 Profile](#6.2_Profile)


[7 Catalogues](#7_Catalogues)


[7.1 Klassen](#7.1)


[7.2 ProNameItem](#7.2_ProNameItem)


[7.3 ProNameRef](#7.3_ProNameRef)


[7.4 ProScaleItem](#7.4_ProScaleItem)


[7.5 ProScaleRef](#7.5_ProScaleRef)


[7.6 ProSectionTypeItem](#7.6_ProSectionTypeItem)


[7.7 ProSectionTypeRef](#7.7_ProSectionTypeRef)




# Paketstruktur


[1 UML\_DM\_GA25\_Profiles\_V1](#1_UML_DM_GA25_Profiles_V1)


[2 DM\_GA25\_Profiles\_V1.ili](#2_DM_GA25_Profiles_V1.ili)


[4 DM\_GA25\_Profiles\_V1](#4_DM_GA25_Profiles_V1)


[4.3 LineStructure](#4.3_LineStructure)


[4.4 MultiLine](#4.4_MultiLine)


[6 Profiles](#6_Profiles)


[6.2 Profile](#6.2_Profile)


[3 GA25\_ProfilesCatalogues\_V1.ili](#3_GA25_ProfilesCatalogues_V1.ili)


[5 GA25\_ProfilesCatalogues\_V1](#5_GA25_ProfilesCatalogues_V1)


[7 Catalogues](#7_Catalogues)


[7.2 ProNameItem](#7.2_ProNameItem)


[7.3 ProNameRef](#7.3_ProNameRef)


[7.4 ProScaleItem](#7.4_ProScaleItem)


[7.5 ProScaleRef](#7.5_ProScaleRef)


[7.6 ProSectionTypeItem](#7.6_ProSectionTypeItem)


[7.7 ProSectionTypeRef](#7.7_ProSectionTypeRef)




# 1 UML\_DM\_GA25\_Profiles\_V1


## 1.1 Pakete


* [DM\_GA25\_Profiles\_V1.ili](#2_DM_GA25_Profiles_V1.ili)
* [GA25\_ProfilesCatalogues\_V1.ili](#3_GA25_ProfilesCatalogues_V1.ili)


# 2 DM\_GA25\_Profiles\_V1.ili


## 2.1 Pakete


* [DM\_GA25\_Profiles\_V1](#4_DM_GA25_Profiles_V1)


# 3 GA25\_ProfilesCatalogues\_V1.ili


## 3.1 Pakete


* [GA25\_ProfilesCatalogues\_V1](#5_GA25_ProfilesCatalogues_V1)


# 4 DM\_GA25\_Profiles\_V1


Data model GA25\_PROFILES - Datenmodell GA25\_PROFILE - Modèle de données AG25\_COUPES

minimal geodata model, topic: GA25\_ProfilesCatalogues, provider: swisstopo / SWISS GEOLOGICAL SURVEY


## 4.1 Pakete


* [Profiles](#6_Profiles)


## 4.2 Klassen


* [LineStructure](#4.3_LineStructure)
* [MultiLine](#4.4_MultiLine)


## 4.3 LineStructure







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Line | 0..1 | Line |  |


## 4.4 MultiLine







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Lines | 1..n |  |  |


# 5 GA25\_ProfilesCatalogues\_V1


Data model GA25\_PROFILES (CATALOGUES) - Datenmodell GA25\_PROFILE (KATALOG) - Modèle de données AG25\_COUPES\_GÉOLOGIQUES (CATALOGUES)

GA25\_ProfilesCatalogues belongs to the minimal geodata model, topic: GA25\_ProfilesCatalogues, provider: swisstopo / SWISS GEOLOGICAL SURVEY


## 5.1 Pakete


* [Catalogues](#7_Catalogues)


# 6 Profiles


Topic of data model DM\_GA25\_Profiles\_V1


## 6.1 Klassen


* [Profile](#6.2_Profile)


## 6.2 Profile







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Geometry | 1 |  | Geometry: Geometry of the corresponding object type |
| GA25\_ID | 1 | Zeichenkette | GA25\_ID: Object ID merged out of plate and section numbers |
| GA25\_No | 1 | 0..999 | GA25\_No: Number of the geological map |
| GA25\_Name | 1 |  | GA25\_Name: Name of the geological map |
| GA25\_Edition | 1 | 1900..2200[Y] | GA25\_Edition: Year of the publication of the geological map |
| Plate\_No | 1 | Zeichenkette | Plate\_No: Plate number of cross-section |
| Section\_No | 1 | Zeichenkette | Section\_No: Section number of cross-section |
| Section\_Type | 1 |  | Section\_Type: Type of the geological cross-section |
| Scale | 1 |  | Scale: Scale of the cross-section |
| Vert\_Exag | 1 | 0.0..20.0 | Vert\_Exag: Vertical exageration of cross-section |
| Author | 1 | Zeichenkette | Author: Author(s) of the geological map or cross-section |
| Link\_Original | 1 | Zeichenkette | Link\_Original: Original path of Document |
| Link\_Onlineshop\_D | 1 | Zeichenkette | Link\_Onlineshop\_D: Link of the Onlineshop (DE) |
| Link\_Onlineshop\_F | 1 | Zeichenkette | Link\_Onlineshop\_F: Link of the Onlineshop (FR) |
| Link\_Onlineshop\_I | 1 | Zeichenkette | Link\_Onlineshop\_I: Link of the Onlineshop (IT) |
| Link\_Onlineshop\_E | 1 | Zeichenkette | Link\_Onlineshop\_E: Link of the Onlineshop (EN) |
| Link\_swissgeol\_D | 1 | Zeichenkette | Link\_swissgeol\_D: Link of swissgeol webpage (DE) |
| Link\_swissgeol\_F | 1 | Zeichenkette | Link\_swissgeol\_F: Link of swissgeol webpage (FR) |
| Link\_swissgeol\_I | 1 | Zeichenkette | Link\_Onlineshop\_I: Link of swissgeol webpage (IT) |
| Link\_swissgeol\_E | 1 | Zeichenkette | Link\_Onlineshop\_E: Link of swissgeol webpage (EN) |


# 7 Catalogues


Topic für Datenmodell GA25\_ProfilesCatalogues

Definition einer UUID für alle Klassen des Modells


## 7.1 Klassen


* [ProNameItem](#7.2_ProNameItem)
* [ProNameRef](#7.3_ProNameRef)
* [ProScaleItem](#7.4_ProScaleItem)
* [ProScaleRef](#7.5_ProScaleRef)
* [ProSectionTypeItem](#7.6_ProSectionTypeItem)
* [ProSectionTypeRef](#7.7_ProSectionTypeRef)


## 7.2 ProNameItem


Name of the geological map







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| GeolCode | 0..1 | Zeichenkette |  |
| Name | 1 | Zeichenkette |  |
| Description | 0..1 |  |  |
| ProNameRef |  | ProNameRef |  |


## 7.3 ProNameRef







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Reference | 1 | ProNameItem |  |


## 7.4 ProScaleItem


Scale of the cross-section







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| GeolCode | 0..1 | Zeichenkette |  |
| Name | 1 | Zeichenkette |  |
| Description | 0..1 |  |  |
| ProScaleRef |  | ProScaleRef |  |


## 7.5 ProScaleRef







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Reference | 1 | ProScaleItem |  |


## 7.6 ProSectionTypeItem


Type of the geological cross-section







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| GeolCode | 0..1 | Zeichenkette |  |
| Name | 1 |  |  |
| Description | 0..1 |  |  |
| ProSectionTypeRef |  | ProSectionTypeRef |  |


## 7.7 ProSectionTypeRef







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Reference | 1 | ProSectionTypeItem |  |




# Index der Modellelemente




 A 
 B 
 [C](#Catalogues)
[D](#DM_GA25_Profiles_V1)
 E 
 F 
 [G](#GA25_ProfilesCatalogues_V1)
 H 
 I 
 J 
 K 
 [L](#LineStructure)
[M](#MultiLine)
 N 
 O 
 [P](#ProNameItem)
 Q 
 R 
 S 
 T 
 [U](#UML_DM_GA25_Profiles_V1)
 V 
 W 
 X 
 Y 
 Z 



  

[Catalogues 7](#7_Catalogues)


[DM\_GA25\_Profiles\_V1 4](#4_DM_GA25_Profiles_V1)


[DM\_GA25\_Profiles\_V1.ili 2](#2_DM_GA25_Profiles_V1.ili)


[GA25\_ProfilesCatalogues\_V1 5](#5_GA25_ProfilesCatalogues_V1)


[GA25\_ProfilesCatalogues\_V1.ili 3](#3_GA25_ProfilesCatalogues_V1.ili)


[LineStructure 4.3](#4.3_LineStructure)


[MultiLine 4.4](#4.4_MultiLine)


[ProNameItem 7.2](#7.2_ProNameItem)


[ProNameRef 7.3](#7.3_ProNameRef)


[ProScaleItem 7.4](#7.4_ProScaleItem)


[ProScaleRef 7.5](#7.5_ProScaleRef)


[ProSectionTypeItem 7.6](#7.6_ProSectionTypeItem)


[ProSectionTypeRef 7.7](#7.7_ProSectionTypeRef)


[Profile 6.2](#6.2_Profile)


[Profiles 6](#6_Profiles)


[UML\_DM\_GA25\_Profiles\_V1 1](#1_UML_DM_GA25_Profiles_V1)





