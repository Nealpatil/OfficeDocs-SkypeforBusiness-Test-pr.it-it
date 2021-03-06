﻿---
title: 'Lync Server 2013: tblEnumValue'
TOCTitle: tblEnumValue
ms:assetid: a33df20c-d19d-4f5c-b012-29dab8fb9200
ms:mtpsurl: https://technet.microsoft.com/it-it/library/Gg615025(v=OCS.15)
ms:contentKeyID: 49301526
ms.date: 08/24/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# tblEnumValue in Lync Server 2013

 

_**Ultima modifica dell'argomento:** 2015-03-09_

tblEnumValue è una tabella hardcoded contenente i valori Visibility e Behavior degli attributi utilizzati nella tabella Node.

### Colonne

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Colonna</th>
<th>Tipo</th>
<th>Descrizione</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>valueID</p></td>
<td><p>smallint, not null</p></td>
<td><p>ID del valore.</p></td>
</tr>
<tr class="even">
<td><p>attributeID</p></td>
<td><p>smallint, not null</p></td>
<td><p>ID dell'attributo.</p></td>
</tr>
<tr class="odd">
<td><p>attributeValue</p></td>
<td><p>nvarchar (256), not null</p></td>
<td><p>Nome del valore.</p></td>
</tr>
</tbody>
</table>


### Chiavi

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Colonna</th>
<th>Descrizione</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>valueID</p></td>
<td><p>Chiave primaria.</p></td>
</tr>
<tr class="even">
<td><p>attributeID</p></td>
<td><p>Chiave esterna con ricerca nella tabella tblEnumAttribute.attributeID.</p></td>
</tr>
</tbody>
</table>


### Valori della tabella

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>valueID</th>
<th>attributeID</th>
<th>attributeValue</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>2</p></td>
<td><p>1</p></td>
<td><p>private</p></td>
</tr>
<tr class="even">
<td><p>3</p></td>
<td><p>1</p></td>
<td><p>scope</p></td>
</tr>
<tr class="odd">
<td><p>4</p></td>
<td><p>2</p></td>
<td><p>normal</p></td>
</tr>
<tr class="even">
<td><p>5</p></td>
<td><p>2</p></td>
<td><p>auditorium</p></td>
</tr>
<tr class="odd">
<td><p>6</p></td>
<td><p>1</p></td>
<td><p>open</p></td>
</tr>
</tbody>
</table>


## Vedere anche

#### Concetti

[tblNode in Lync Server 2013](lync-server-2013-tblnode.md)

