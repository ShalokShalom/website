---
ID: 492
post_title: '<!--:en-->Known issue with measured pO2 reported by some CCR dive computers<!--:--><!--:de-->Fehler beim Speichern der gemessenen pO2 Werte von einigen Tauchcomputern, die mit Kreislauftauchgeräten genutzt werden<!--:--><!--:fr-->Problème connu avec la valeur pO2 rapportée par certains ordinateurs de plongée CCR (recycleur en circuit fermé)<!--:-->'
author: hohndel
post_date: 2013-03-02 16:45:43
post_excerpt: ""
layout: post
permalink: >
  https://subsurface-divelog.org/2013/03/known-issue-with-measured-po2-reported-by-some-ccr-dive-computers/
published: true
---
<!--:en-->While this won't affect the majority of our users, for those diving rebreathers with connected dive computers that measure and report pO2 during the dive (e.g. Shearwater Predator and Petrel): there is a bug in the way we store the pO2 in our data files. This bug causes us to corrupt some of the pO2 values in our data file; this often creates odd spikes in the pO2 graph.

A version 3.0.2 that fixes that should be out within the next day or two - the goal is that users affected simply need to re-download their dives from their dive computer with that updated version of Subsurface; that should correct the problem without any data loss. We still need to do some more testing to make sure that does indeed work as intended.<!--:--><!--:de-->Dieses Problem betrifft die Masse unserer Benutzer nicht, aber für jene Taucher, die mit Kreislauftauchgeräten mit angeschlossenen Tauchcomputern unterwegs sind, und deren Tauchcomputer dann die gemessenen pO2 Werte speichern (z.B. Shearwater Predator und Petrel) möchten wir folgenden Hinweis geben: Subsurface 3.0 und 3.0.1 haben einen Fehler beim Speichern dieser pO2 Daten, der dazu führen kann, dass die Daten verfälscht werden.

Wir planen in den nächsten zwei Tagen die neue Subsurface Version 3.0.2 zu veröffentlichen, welche dieses Problem beheben wird. Angestrebt wird, dass ein betroffener Benutzer einfach die Daten erneut vom Tauchcomputer herunterladen kann und dann ohne Datenverlust das Problem behoben ist. Im Moment testen wir unsere Lösung um sicherzustellen, dass sie wie geplant funktioniert.<!--:--><!--:fr-->Bien que cela n'affecte pas la majorité de nos utilisateurs, pour ceux qui plongent avec un recycleur en circuit fermé et un ordinateur de plongée relié renvoyant la valeur pO2 pendant la plongée (par exemple le Shearwater Predator ou le Petrel): il y a un bug dans la façon dont nous stockons la valeur pO2. Ce bug peut corrompre quelques-unes des valeurs de pO2 dans le fichier de données, ce qui crée souvent des pointes anormales dans le graphique pO2.

Une version 3.0.2 qui fixe ce problème devrait sortie dans un jour ou deux - le but étant que les utilisateurs touchés auront juste à retélécharger leurs plongées à partir de leur ordinateur de plongée avec cette version mise à jour de Subsurface; ce qui devrait corriger le problème sans perte de données. Nous avons encore besoin de faire des tests pour nous assurer que cela fonctionne comme prévu.<!--:-->