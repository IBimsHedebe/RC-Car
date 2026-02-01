# Tagebuch

## Eintrag vom 19. Dezember 2025
Heute habe ich mit dem neuen Projekt angefangen. Die ersten Teile für mein Projekt wurden bestellt.
- M3 und M4 Schrauben (https://amzn.eu/d/2Jg72SI)
- 2.4Ghz RC Sender und Empfänger (https://amzn.eu/d/0u21GuM)
- Gewindeeinsätze (https://amzn.eu/d/4eelvHs)
- Batteriehalter für 3x AA Batterien (https://amzn.eu/d/4DOVe0m)

Ich habe erstmal nur diese Sachen bestellt, da ich erst mit der Lenkung anfangen möchte. Ein Servo ist dort nicht vorhanden da ich schon einen zuhause habe (SG90).

## Eintrag vom 20. - 21. Dezember 2025
Ich habe mit der ersten Version von der Lenkung angefangen. Diese besteht momentan nur aus einem Viereck gelenk zum drehen der Reifen und einem Hebelarm zur Federung. Das Design ist nur ein Work of Progress und ist moch lange nicht das fertig Produkt.
- [Lenkung V1](../Dokumentation/Bilder/Lenkung_V1.png)
- [Lenkung V1 Dateien](../Dokumentation/3D_Modelle/Lenkung_V1.f3d)

## Eintrag vom 23. Dezember 2025
Bevor ich aber mit dem ersten Design der Lenkung anfange, habe ich mit der Elektrotechnik angefangen. Dort habe ich im Internet nachgeschaut um herauszufinden wie ich mit den Empfänger den Servo für die Lenkung ansteuer. 
Da ist aufgefallen das meine bestellte Batteriehalter mit den 3x AA Baterien nicht ausreicht und habe dann meinen etwas älteren Batteriehalter für 4x AA Baterien benutzt mit dem das dann auch ging.
- [Schaltkreisplan Lenkung](../Dokumentation/Bilder/Schaltkreisplan_Lenkung.png)]

## Eintrag vom 28. Dezember 2025
Ich habe noch ein paar alte 4.8V Batterien gefunden die ich dann für den Servo benutzt habe. Auch habe ich mit noch ein paar weitere Werkzeuge und nötige Teile bestellt.
- Lötgerät (https://amzn.eu/d/4l14aaJ)
- Mosfet Modul (https://amzn.eu/d/cuaSOAF)

Das Lötgerät habe ich mir bestellt, da ich dafor noch keins hatte und ich das für die Elektrotechnik benötige.
Das Mosfet Modul habe ich bestellt, da sehen wollte ob ich einen alten 130er Motor mit dem Empfänger und Reciever steuern kann. Die Antwort ist nein nicht wirklich, da man zwar mit dem Motor vorwärts fahren könnte aber nicht stehen bleiben, oder rückwärts fahren kann. Das liegt daran, das der Reciever immer eine Spannung übergibt und der Mosfetdadurch immer Spannung zu den Motor durchlässt.
Daher werde ich für den Antrieb einen ESC (Electronic Speed Controller) benötigen und auch einen besseren Motor. Das Set was ich mir rausgesucht habe ist folgendes:
- ESC und Motor (https://amzn.eu/d/33luHVY)

anschließend musste ich mir auch eine passende Batterie für den Motor bestellen, da die alten 4.8V Batterien nicht ausreichen werden. Ich habe mich für eine 7.4V 2s LiPo Batterie entschieden und ein passenden Ladegerät dazu.
- 7.4V 2s LiPo Batterie (https://amzn.eu/d/4924E3n)
- LiPo Ladegerät (https://amzn.eu/d/4fIGWro)

Ich habe mir dann auch noch ein paar weitere Uteensilien bestellt die ich für das Projekt benötigen könnte.
- Wiederstände Set (https://amzn.eu/d/ebyYEvR)
- Schrumpfschlauch Set (https://amzn.eu/d/fTmEgeS)
- Keramik Kondensator Set (https://amzn.eu/d/0SDwGgC)

## Eintrag vom 7. Januar 2026
Heute sind die letzten bestellten Teile angekommen. Ich habe zwar auch schon eine zweite Version gemacht, habe aber die Dateien davon Verloren. Also habe ich V3 der Lenkung gemacht. Diese ist deutlich besser, da ich hier versucht habe die Feder starr zu befestigen, was nicht wirklich funktionierte. und zur Federung nutzte ich jetzt die viereck Gelenke die ich in V1 als Lenkung benutzt habe.
Hier habe ich aber statt eine viereck Lenkung, den Servo benutzt um aus der Rotierenden Bewegung eine Lineare Bewegung zu machen, aber dazu kam ich nicht.
- [Lenkung V3](../Dokumentation/Bilder/Lenkung_V3.png)
- [Lenkung V3 Dateien](../Dokumentation/3D_Modelle/Lenkung_V3.f3z)

Außerdem sind mir ein paar Probleme aufgefallen:
- Das Kugelgelenk gibt mir nicht genug Freiraum um meine Federung funktional zu machen.
- Die Feder hat immer noch zu viel Spielraum.

## Eintrag vom 18. - 29. Januar 2026
Ich habe mir überlegt die Lenkung nochmal von neu anzufangen. Bei V4 habe ich jetzt das Kugelgelenk durch ein einfaches Schanier ersetzt. Auch habe ich die Feder jetzt seperat von der Achse wo ich das Rad befestigen möchte angebracht. Auch habe ich das gesamte design deutlich kleiner gemacht als V1 - V3. Die Federung habe ich auch stabilisierne können indem ich sie auf stangen gehängt habe und links sowie rechts davon Abstandhalter befästigt.
Das was nun noch fehlt ist die Anbringung der Reifen und das Implementieren der Lenkung mit dem Servo.
Bevor ich das aber mache, sind mir noch ein paar Probleme aufgefallen:
- Die Federung hat jetzt in der y-Achse zu wenig Spielraum und kann fast gar nicht mehr federn.

- [Lenkung V4](../Dokumentation/Bilder/Lenkung_V4.png))
- [Lenkung V4 Dateien](../Dokumentation/3D_Modelle/Lenkung_V4.f3z)

## Eintrag vom 29. Januar 2026
Ich habe jetzt die nächste Version V5 der Lenkung angefangen. Dort ist das Prinzip der Federung eingentlich gleich geblieben nur die Fehler vom vorgänger wurden behoben. Auch wurde die Lenkung mit dem Servo angegangen. Meine Grundsätzliche Idee ist es das der Servo ein Zahnrad dreht und das dan zwei Racks rechst und links davon bewegt. Diese Racks sind dann mit den Hebelarmen verbunden die die Räder lenken.
Nur bei der Radaufhängung habe ich nicht bedacht das wenn ich sie um den Schaft von der Gefederten Seite umlege, das die Federung komplett ignoriert wird.

Probleme die noch bestehen:
- Die Federung wird Ignoriert wenn ich die Radaufhängung um den Schaft der Gefederten Seite umlege.
- Wenn ich die Reifen anbringe, kollidieren sie mit der Aufhängung.
- Die Reifen können sich nicht wegen der Aufhängung drehen (Form momentan Sechseck, sollte Kreis sein).

- [Lenkung V5.1](../Dokumentation/Bilder/Lenkung_V5.1.png))
- [Lenkung V5.1 Dateien](../Dokumentation/3D_Modelle/Lenkung_V5.1.f3z)

## Eintrag vom 31. Januar 2026
Ich habe Die Aufhängung ein wenig überarbeitet. Jetzt kollidieren die Reifen nicht mehr mit der Aufhängung und lassen sich auch drehen, wenn sie angebracht werden.
Neue Probleme die noch bestehen:
- Das Lenken funktioniert nicht mehr, da sich die Radaufhängung mit dem Rack verkantet.
- Die Radaufhängung sich nicht gerade hoch und runter bewegen, sodern erher kreisförmig.

- [Lenkung V5.2](../Dokumentation/Bilder/Lenkung_V5.2.png))
- [Lenkung V5.2 Dateien](../Dokumentation/3D_Modelle/Lenkung_V5.2.f3z)

## Eintrag vom 1. Februar 2026
Heute habe ich die Radaufhängung im großen und ganzen überarbeitet. Ich habe viele Test Versionen gemacht und auch fast alle getestet und alle mir aufgefallene Probleme behoben.
Jetzt muss ich nur noch die Letzten Teile ausdrucken und zusammenbauen, um zu seghen ob alles so funktioniert wie ich es mir vorstelle.

Mir sind viele Fehler begegnet. Zum einen hatte das Rack keinen Spielraum zum drehen wesshalb es sich immer verbog und irgendwann verkeilte. 
Als ich dies behob und druckte, viel mir auf das es nicht mehr in die originale Halterung an den Seiten passte. Diese habe ich dann auch überarbeitet aber noch nicht testen können, was ich morgen nachgehen werde.

Dann habe ich auch noch platz Probleme gehabt die ich beheben musste. Die Aufhängung für die Reifen hatten zu wenig Freiraum zur Viereckfederung und kolidierten ständig.

Ansonsten verlief der Tag ganz gut und ich bin zufrieden mit dem Fortschritt.

- [Lenkung V5.3](../Dokumentation/Bilder/Lenkung_V5.3.png))
- [Lenkung V5.3 Dateien](../Dokumentation/3D_Modelle/Lenkung_V5.3.f3z)