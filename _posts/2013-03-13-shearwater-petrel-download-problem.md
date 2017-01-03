---
ID: 570
post_title: '<!--:en-->Shearwater Petrel download problem<!--:--><!--:de-->Probleme mit dem Shearwater Petrel<!--:--><!--:fr-->Problème de téléchargement avec le Shearwater Petrel<!--:--><!--:es-->Problema con las descargas desde el Shearwater Petrel <!--:--><!--:pl-->Problem z pobieraniem danych z Shearwater Petrel<!--:-->'
author: hohndel
post_date: 2013-03-13 10:53:29
post_excerpt: ""
layout: post
permalink: >
  https://subsurface-divelog.org/2013/03/shearwater-petrel-download-problem/
published: true
---
<!--:en-->We are working with <a href="http://www.shearwaterresearch.com/">Shearwater Research</a> on a slightly odd problem when downloading data from their Shearwater Petrel dive computer. From what we have been able to analyze (with generous help and support from Shearwater Research) it appears that the current firmware version of the Petrel causes a strange interaction with the libdivecomputer routines used to download divelog information from the Petrel.

At this point there appears to be no easy to implement workaround - Shearwater Research is working on a firmware update for the Petrel that will fix the issue, but a release date for that update is not yet known. In the meantime we are working on implementing a <em>different</em> downloading algorithm for the Petrel that should also work around the issue, but we don't have an educated guess when that will be finished, either.

So the disappointing status right now is that Petrels running firmware v8 and v11 are not supported in Subsurface.<!--:--><!--:de-->Wir arbeiten zusammen mit <a href="http://www.shearwaterresearch.com/">Shearwater Research</a> an einem seltsamen Problem beim Herunterladen von Tauchlogbuch-Einträgen vom Shearwater Petrel Tauchcomputer. Unsere Analyse (mit tatkräftiger Unterstützung durch Shearwater Research) hat ergeben, dass das Problem anscheinend von der Petrel Firmware verursacht wird.

Im Moment sehen wir keine einfache Möglichkeit, das Problem zu umgehen. Shearwater Research arbeitet an einer neuen Firmware, die das Problem beheben wird, leider steht aber noch kein Veröffentlichungs-Zeitpunkt für diese neue Version fest. Gleichzeitig arbeiten wir daran, einen alternativen Algorithmus zum Herunterladen von Daten vom Shearwater Petrel zu implementieren, haben aber auch hierfür keine gute Zeitabschätzung.

Im Moment ist die enttäuschende Zusammenfassung, dass Petrels mit Firmware v8 oder v11 von Subsurface nicht unterstützt werden.<!--:--><!--:fr-->Nous travaillons avec Shearwater Research sur un problème étrange lors du téléchargement de données à partir de leur ordinateur de plongée Shearwater Petrel. D'après ce que nous avons pu analyser (avec l'aide généreuse et le soutien de Shearwater Research), il semblerai que la version actuelle du firmware du Petrel provoque une étrange interaction avec les routines libdivecomputer utilisées pour télécharger les informations de plongée.

A ce stade, il ne semble pas facile à mettre en oeuvre solution de contournement - Shearwater Research travaille sur une mise à jour du firmware pour le Petrel qui permettra de régler le problème, mais une aucune date de sortie pour cette mise à jour n'est annoncée. En attendant, nous travaillons sur la mise en œuvre d'un algorithme de téléchargement différent pour le Petrel qui devrait également régler le problème, mais nous n'avons encore aucune idée du temps que cela prendra.

Du coup, malheureusement pour le moment, les modèles Petrels utilisant les firmware v8 et v11 ne sont pas pris en charge dans Subsurface.<!--:--><!--:es-->Estamos trabajando con <a href="http://www.shearwaterresearch.com/">Shearwater Research</a> en un problema un poco raro que se produce al descargar datos desde el ordenador de buceo Shearwater Petrel. Por lo que hemos podido analizar (con la generosa ayuda y apoyo de Shearwater Research) parece que la versión actual del firmware del Petrel causa una interacción extraña con las rutinas de libdivecomputer utilizadas para descargar la información de las inmersiones.

En este punto no parece haber una solución fácil de implementar - Shearwater Research está trabajando en una actualización del firmware del Petrel que solucionará el problema, pero aún no se conoce una fecha de lanzamiento. Mientras tanto estamos trabajando para implementar un algoritmo de descarga <em>diferente</em> para el Petrel que también debería resolver el problema, pero no tenemos, tampoco, una idea aproximada de cuando la tendremos finalizada.

Por lo tanto, el desagradable estado actual es que los Petrel con firmware V8 y V11 no están soportados en Subsurface.<!--:--><!--:pl-->Współpracujemy z <a href="http://www.shearwaterresearch.com/">Shearwater Research</a> nad nietypowym problemem dotyczącym pobierania danych z komputera Shearwater Petrel. Z dotychczasowych analiz wynika, że obecna wersja firmware dla Petrel zachowuje się w dziwny sposób podczas współpracy z funkcjami z libdivecomputer odpowiedzialnymi za pobieranie danych.

Na chwile obecną nie ma prostego rozwiązania - Shearwater Research pracuje nad uaktualnieniem firmware dla Petrel ale data jego udostępnienia nie jest na razie znana.

Na razie komputery Petrel z firmware v8  v11 nie działają z Subsurface.<!--:-->