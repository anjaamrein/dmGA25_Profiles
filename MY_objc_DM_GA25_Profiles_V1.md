

Objektkatalog des Paketes UmlModel1
A {text-decoration: none }TD{border-bottom: solid black; border-bottom-width: 1px}


# Inhalt


[1 UmlModel1](#1_UmlModel1)


[1.1 Pakete](#1.1_Packages)


[2 INTERLIS2Def3](#2_INTERLIS2Def3)


[2.1 Pakete](#2.1_Packages)


[3 eingelesen1](#3_eingelesen1)


[3.1 Pakete](#3.1_Packages)


[4 ModelDef4](#4_ModelDef4)


[4.1 Pakete](#4.1_Packages)


[5 DM\_GA25\_Profiles\_V1.ili](#5_DM_GA25_Profiles_V1.ili)


[5.1 Pakete](#5.1_Packages)


[6 GA25\_ProfilesCatalogues\_V1.ili](#6_GA25_ProfilesCatalogues_V1.ili)


[6.1 Pakete](#6.1_Packages)


[7 TopicDef5](#7_TopicDef5)


[8 DM\_GA25\_Profiles\_V1](#8_DM_GA25_Profiles_V1)


[8.1 Pakete](#8.1_Packages)


[8.2 Klassen](#8.2)


[8.3 LineStructure](#8.3_LineStructure)


[8.4 MultiLine](#8.4_MultiLine)


[9 GA25\_ProfilesCatalogues\_V1](#9_GA25_ProfilesCatalogues_V1)


[9.1 Pakete](#9.1_Packages)


[10 Profiles](#10_Profiles)


[10.1 Klassen](#10.1)


[10.2 Profile](#10.2_Profile)


[11 Catalogues](#11_Catalogues)


[11.1 Klassen](#11.1)


[11.2 ProNameItem](#11.2_ProNameItem)


[11.3 ProNameRef](#11.3_ProNameRef)


[11.4 ProScaleItem](#11.4_ProScaleItem)


[11.5 ProScaleRef](#11.5_ProScaleRef)


[11.6 ProSectionTypeItem](#11.6_ProSectionTypeItem)


[11.7 ProSectionTypeRef](#11.7_ProSectionTypeRef)




# Paketstruktur


[1 UmlModel1](#1_UmlModel1)


[2 INTERLIS2Def3](#2_INTERLIS2Def3)


[4 ModelDef4](#4_ModelDef4)


[7 TopicDef5](#7_TopicDef5)


[3 eingelesen1](#3_eingelesen1)


[5 DM\_GA25\_Profiles\_V1.ili](#5_DM_GA25_Profiles_V1.ili)


[8 DM\_GA25\_Profiles\_V1](#8_DM_GA25_Profiles_V1)


[8.3 LineStructure](#8.3_LineStructure)


[8.4 MultiLine](#8.4_MultiLine)


[10 Profiles](#10_Profiles)


[10.2 Profile](#10.2_Profile)


[6 GA25\_ProfilesCatalogues\_V1.ili](#6_GA25_ProfilesCatalogues_V1.ili)


[9 GA25\_ProfilesCatalogues\_V1](#9_GA25_ProfilesCatalogues_V1)


[11 Catalogues](#11_Catalogues)


[11.2 ProNameItem](#11.2_ProNameItem)


[11.3 ProNameRef](#11.3_ProNameRef)


[11.4 ProScaleItem](#11.4_ProScaleItem)


[11.5 ProScaleRef](#11.5_ProScaleRef)


[11.6 ProSectionTypeItem](#11.6_ProSectionTypeItem)


[11.7 ProSectionTypeRef](#11.7_ProSectionTypeRef)




# 1 UmlModel1




|  |  |
| --- | --- |
| *Author:* |  |
| *Version:* |  |


## 1.1 Pakete


* [INTERLIS2Def3](#2_INTERLIS2Def3)
* [eingelesen1](#3_eingelesen1)


# 2 INTERLIS2Def3


## 2.1 Pakete


* [ModelDef4](#4_ModelDef4)


# 3 eingelesen1


## 3.1 Pakete


* [DM\_GA25\_Profiles\_V1.ili](#5_DM_GA25_Profiles_V1.ili)
* [GA25\_ProfilesCatalogues\_V1.ili](#6_GA25_ProfilesCatalogues_V1.ili)


# 4 ModelDef4


## 4.1 Pakete


* [TopicDef5](#7_TopicDef5)


# 5 DM\_GA25\_Profiles\_V1.ili


## 5.1 Pakete


* [DM\_GA25\_Profiles\_V1](#8_DM_GA25_Profiles_V1)


# 6 GA25\_ProfilesCatalogues\_V1.ili


## 6.1 Pakete


* [GA25\_ProfilesCatalogues\_V1](#9_GA25_ProfilesCatalogues_V1)


# 7 TopicDef5


# 8 DM\_GA25\_Profiles\_V1


Data model GA25\_PROFILES - Datenmodell GA25\_PROFILE - Modèle de données AG25\_COUPES

minimal geodata model, topic: GA25\_ProfilesCatalogues, provider: swisstopo / SWISS GEOLOGICAL SURVEY


## 8.1 Pakete


* [Profiles](#10_Profiles)


## 8.2 Klassen


* [LineStructure](#8.3_LineStructure)
* [MultiLine](#8.4_MultiLine)


## 8.3 LineStructure







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Line | 0..1 | Line |  |


## 8.4 MultiLine







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Lines | 1..n |  |  |


# 9 GA25\_ProfilesCatalogues\_V1


Data model GA25\_PROFILES (CATALOGUES) - Datenmodell GA25\_PROFILE (KATALOG) - Modèle de données AG25\_COUPES\_GÉOLOGIQUES (CATALOGUES)

GA25\_ProfilesCatalogues belongs to the minimal geodata model, topic: GA25\_ProfilesCatalogues, provider: swisstopo / SWISS GEOLOGICAL SURVEY


## 9.1 Pakete


* [Catalogues](#11_Catalogues)


# 10 Profiles


Topic of data model DM\_GA25\_Profiles\_V1


## 10.1 Klassen


* [Profile](#10.2_Profile)


## 10.2 Profile







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


# 11 Catalogues


Topic für Datenmodell GA25\_ProfilesCatalogues

Definition einer UUID für alle Klassen des Modells


## 11.1 Klassen


* [ProNameItem](#11.2_ProNameItem)
* [ProNameRef](#11.3_ProNameRef)
* [ProScaleItem](#11.4_ProScaleItem)
* [ProScaleRef](#11.5_ProScaleRef)
* [ProSectionTypeItem](#11.6_ProSectionTypeItem)
* [ProSectionTypeRef](#11.7_ProSectionTypeRef)


## 11.2 ProNameItem


Name of the geological map







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| GeolCode | 0..1 | Zeichenkette |  |
| Name | 1 | Zeichenkette |  |
| Description | 0..1 |  |  |
| ProNameRef |  | ProNameRef |  |


## 11.3 ProNameRef







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Reference | 1 | ProNameItem |  |


## 11.4 ProScaleItem


Scale of the cross-section







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| GeolCode | 0..1 | Zeichenkette |  |
| Name | 1 | Zeichenkette |  |
| Description | 0..1 |  |  |
| ProScaleRef |  | ProScaleRef |  |


## 11.5 ProScaleRef







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Reference | 1 | ProScaleItem |  |


## 11.6 ProSectionTypeItem


Type of the geological cross-section







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| GeolCode | 0..1 | Zeichenkette |  |
| Name | 1 |  |  |
| Description | 0..1 |  |  |
| ProSectionTypeRef |  | ProSectionTypeRef |  |


## 11.7 ProSectionTypeRef







| Name | Kardinalität | Typ | Beschreibung |
| --- | --- | --- | --- |
| Reference | 1 | ProSectionTypeItem |  |




# Index der Modellelemente




 A 
 B 
 [C](#Catalogues)
[D](#DM_GA25_Profiles_V1)
[E](#eingelesen1)
 F 
 [G](#GA25_ProfilesCatalogues_V1)
 H 
 [I](#INTERLIS2Def3)
 J 
 K 
 [L](#LineStructure)
[M](#ModelDef4)
 N 
 O 
 [P](#ProNameItem)
 Q 
 R 
 S 
 [T](#TopicDef5)
[U](#UmlModel1)
 V 
 W 
 X 
 Y 
 Z 



  

[Catalogues 11](#11_Catalogues)


[DM\_GA25\_Profiles\_V1 8](#8_DM_GA25_Profiles_V1)


[DM\_GA25\_Profiles\_V1.ili 5](#5_DM_GA25_Profiles_V1.ili)


[GA25\_ProfilesCatalogues\_V1 9](#9_GA25_ProfilesCatalogues_V1)


[GA25\_ProfilesCatalogues\_V1.ili 6](#6_GA25_ProfilesCatalogues_V1.ili)


[INTERLIS2Def3 2](#2_INTERLIS2Def3)


[LineStructure 8.3](#8.3_LineStructure)


[ModelDef4 4](#4_ModelDef4)


[MultiLine 8.4](#8.4_MultiLine)


[ProNameItem 11.2](#11.2_ProNameItem)


[ProNameRef 11.3](#11.3_ProNameRef)


[ProScaleItem 11.4](#11.4_ProScaleItem)


[ProScaleRef 11.5](#11.5_ProScaleRef)


[ProSectionTypeItem 11.6](#11.6_ProSectionTypeItem)


[ProSectionTypeRef 11.7](#11.7_ProSectionTypeRef)


[Profile 10.2](#10.2_Profile)


[Profiles 10](#10_Profiles)


[TopicDef5 7](#7_TopicDef5)


[UmlModel1 1](#1_UmlModel1)


[eingelesen1 3](#3_eingelesen1)





