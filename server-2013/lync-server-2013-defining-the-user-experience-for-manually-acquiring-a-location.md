﻿---
title: "Lync Server 2013: Definisce esper. utente per acquisiz. manuale di posizione"
TOCTitle: Definizione dell'esperienza utente per l'acquisizione manuale di una posizione
ms:assetid: d37f67d3-e248-483b-b64c-3986559ef357
ms:mtpsurl: https://technet.microsoft.com/it-it/library/Gg398912(v=OCS.15)
ms:contentKeyID: 49302063
ms.date: 08/24/2015
mtps_version: v=OCS.15
ms.translationtype: HT
---

# Definizione dell'esperienza utente per l'acquisizione manuale di una posizione in Lync Server 2013

 

_**Ultima modifica dell'argomento:** 2012-10-03_

Se un client si trova all'esterno della rete o in una subnet non definita, l'utente può immettere manualmente una posizione. La chiamata di emergenza però verrà innanzitutto instradata a un dispatcher ECRC (Emergency Call Response Center) del servizio E9-1-1 nazionale/regionale prima di essere instradata a un centro di raccolta delle chiamate di emergenza (PSAP, Public Safety Answering Point). Il dispatcher ECRC richiederà verbalmente al chiamante la posizione e inoltrerà quindi la chiamata al centro PSAP appropriato in base alle informazioni fornite.

  - **È necessario richiedere agli utenti l'immissione di una posizione quando il servizio Informazioni percorso non ne specifica una automaticamente?**  
    Se, ad esempio, un client si trova in una subnet non definita, a casa, in un albergo o in qualsiasi altro luogo esterno alla rete, è necessario richiedere all'utente la specifica di una posizione?
    
    È possibile configurare l'impostazione **Posizione obbligatoria** nei criteri percorso per definire il comportamento del client. L'impostazione di questo valore su No indica che all'utente non verrà richiesta una posizione. Se invece si imposta il valore su Sì, all'utente verrà richiesta la specifica della posizione ma potrà ignorare il messaggio. Il valore Dichiarazione di non responsabilità indica invece che all'utente verrà richiesta una posizione e visualizzata una dichiarazione di non responsabilità se tenta di ignorare il messaggio. In tutti i casi, l'utente potrà continuare a utilizzare il client come sempre.

Quando un utente immette manualmente una posizione, tale posizione viene mappata all'indirizzo MAC del gateway predefinito della rete del client e archiviata in una tabella specifica dell'utente disponibile sul client. Quando l'utente ritorna a una posizione archiviata in precedenza, il client Lync viene automaticamente impostato su tale posizione.


> [!NOTE]
> È possibile modificare solo la posizione corrente del client, nonché eliminare le posizioni archiviate nella tabella degli utenti locali.


