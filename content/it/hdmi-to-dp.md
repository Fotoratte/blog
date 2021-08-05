---
title: "HDMI to DisplayPort"
date: 2021-08-05T10:22:30Z
draft: false
tags: [it, hdmi, dp]
---

Heute hatte ich auf der Arbeit ein sehr seltsames Phänomen. 

Ich habe einen neuen Rechner bekommen. Soweit so gut, der alte Rechner war euch etwas in die Jahre gekommen. Nun habe ich jedoch einen DisplayPort-KVM-Switch. Vier DisplayPorts gehen rein, zwei gehen raus. Jedoch hatte der neue Rechner nur einen DisplayPort sowie ein HDMI- und ein DVI-Port. 

Kein Thema dachte ich mir, gibt ja DisplayPort to HDMI Kabel. Also eins davon geschnappt, angesteckt, ging nicht. Hmmm.

Habe es erst auf den KVM-Switch geschoben. Kabel hin und her verschoben, kein Bild. Nach dem Gespräch mit einer Arbeitskollegin wusste ich dann auch, warum. Dieses Problem hatte Sie wohl auch und ist im Netz wohl auch hinreichend bekannt. Jedoch hatte Sie noch einen anderen Adapter. Einen schwarzen Kasten mit DisplayPort, USB- und HDMI-Kabel.

Mit diesem Adapter klappte dann auch die Verbindung, sogar über KVM-Switch. Meine erste Vermutung war, dass der Adapter so etwas wie eine kleine Grafikkarte ist. Jedoch meldete sich im Windows kein neues Gerät an. Somit ist meine aktuelle Vermutung ist, dass DisplayPort mehr Strom benötigt als HDMI. Daher klappt auch eine Verbindung von DisplayPort (viel Strom) zu HDMI (weniger Strom), aber nicht umgekehrt. Und dieser Adapter zieht wahrscheinlich den benötigten Strom aus dem USB-Port.

Woran es nun genau liegt, weiß ich nicht. Ist aber auch egal. Hauptsache zwei Monitore. Anders kann man ja gar nicht arbeiten, oder?

