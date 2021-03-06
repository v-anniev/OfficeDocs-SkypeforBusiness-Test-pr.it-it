﻿---
title: 'Lync Server 2013: Tabella Devices'
TOCTitle: Tabella Devices
ms:assetid: 532e2280-4bbc-4a6c-93da-45d9f80a30a0
ms:mtpsurl: https://technet.microsoft.com/it-it/library/Gg398351(v=OCS.15)
ms:contentKeyID: 49300586
ms.date: 08/24/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# Tabella Devices in Lync Server 2013

 

_**Ultima modifica dell'argomento:** 2015-03-09_

La tabella Devices è una tabella di supporto. In ogni record sono archiviate informazioni relative a un dispositivo (telefono da tavolo).


<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th>Colonna</th>
<th>Tipo di dati</th>
<th>Chiave/indice</th>
<th>Dettagli</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>DeviceId</strong></p></td>
<td><p>int</p></td>
<td><p>Primaria/o</p></td>
<td><p>Numero univoco che identifica questa versione hardware.</p></td>
</tr>
<tr class="even">
<td><p><strong>ManufacturerId</strong></p></td>
<td><p>int</p></td>
<td><p>Esterna</p></td>
<td><p>Produttore del dispositivo. Per ulteriori informazioni, vedere la <a href="lync-server-2013-manufacturers-table.md">Tabella Manufacturers in Lync Server 2013</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>HardwareVersionId</strong></p></td>
<td><p>int</p></td>
<td><p>Esterna</p></td>
<td><p>Versione hardware del dispositivo. Per ulteriori informazioni, vedere la <a href="lync-server-2013-hardwareversions-table.md">Tabella HardwareVersions in Lync Server 2013</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>MacAddress</strong></p></td>
<td><p>bigint</p></td>
<td><p></p></td>
<td><p>Indirizzo MAC</p></td>
</tr>
</tbody>
</table>

