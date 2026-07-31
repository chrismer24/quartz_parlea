---
publish: true
permalink: /5 Regelwerk/Charaktere/Charakterwerte/Trefferschwelle.md
aliases: Beweglichkeitskonstante
description: gibt an, wie schwer schädliche Angriffe auf [[Charaktere]] fallen
created: 2025-06-06T13:27:50.928Z
modified: 2025-10-26T12:46:06.227Z
published: 2025-10-26T12:46:06.227Z
notetype: Charakterwert
tags:
banner: zzz_Assets/Images/Banners/mage_banner.jpg
banner_y: 0.24
---

# Trefferschwelle

Die Trefferschwelle von [[Charaktere|Charakteren]] gibt an, wie schwer es Gegnern fällt, sie ihm Kampf schädlich zu treffen. Dabei kann die Trefferschwelle auf verschiedene Arten erhöht werden. Entweder sind Charaktere bzw. Kreaturen besonders beweglich und können so Angriffen geschickt ausweichen. Oder sie sind besonders robust, sei es durch Rüstung oder dicke Haut. In diesem Fall werden die Charaktere zwar theoretisch auch bei Treffern unterhalb der Schwelle getroffen, diese Treffer richten allerdings keinen Schaden an.

Dieser Wert setzt sich aus der [[Ausstattung#Robustheit|Robustheit]] der getragenen [[Ausstattung]] und einem Anteil des [[Attribute#Attributsboni|Attributsbonus]] [[Agilität]] bzw. [[Konstitution]]. Der daraus resultierende Wert kann durch [[Ausrüstung]], [[Zaubersprüche]] und [[Eigenschaften]] weiter verbessert werden. Er kann während eines Kampfes außerdem mit der [[Fertigkeiten|Fertigkeit]] [[Verteidigen]] nochmals gesteigert werden.

## Berechnung der Trefferschwelle

Die genaue Berechnung der Trefferschwelle unterscheidet sich je nach Art der [[Ausstattung]]. Diese Formel geht dabei immer **vom schwersten Gegenstand** aus.

### Berechnung bei [[Kleidung]]

Wird von Charakteren lediglich [[Kleidung]] getragen, bietet diese zwar keinen Schutz, aber ermöglicht die größte Bewegungsfreiheit. Die Beweglichkeitskonstante fällt daher bei dieser Berechnung mit 8 sehr hoch aus. Die Trefferschwelle ermittelt sich aus folgender Formel:
[[Attribute#Attributsboni|Attributsbonus]] [[Agilität]] oder  [[Attribute#Attributsboni|Attributsbonus]] [[Konstitution]] + 8.

### Berechnung bei [[leichte Rüstung|leichter Rüstung]]

Tragen [[Charaktere]] einen oder mehrere [[Ausstattung|Bekleidungsgegenstände]], welche maximal den [[leichte Rüstung|leichten Rüstungen]] zugeordnet werden, ist ihre Bewegung verglichen mit normaler [[Kleidung]] bereits eingeschränkt, weshalb die Beweglichkeitskonstante hier auf 3 sinkt.
Außerdem kommt neben der eigenen [[Agilität]] auch die körpereigene [[Konstitution]] hier nur noch zur Hälfte zum Einsatz, da die Rüstung nun vermehrt die Treffer abfängt und Charaktere wenn sie diese gewöhnt sind direkte Körpertreffer nicht mehr so gut aushalten können.
Die Trefferschwelle ermittelt sich aus folgender Formel:
halber [[Attribute#Attributsboni|Attributsbonus]] [[Agilität]] oder [[Konstitution]]+ [[Ausstattung#Robustheit|Robustheit]] [[Ausstattung]]+3.

### Berechnung bei [[mittlere Rüstung|mittlerer Rüstung]]

In [[mittlere Rüstung]] fallen Ausweichmanöver bereits sehr schwer, weshalb die Beweglichkeitskonstante entfällt.
Die [[Attribute#Attributsboni|Attributsboni]] werden außerdem nur noch zu einem Drittel berücksichtigt, weshalb sich folgende Formel ergibt:
1/3× [[Attribute#Attributsboni|Attributsbonus]] [[Konstitution]] oder [[Agilität]] + [[Ausstattung#Robustheit|Robustheit]] [[Ausstattung]]

### Berechnung bei [[schwere Rüstung|schwerer Rüstung]]

In schwerer Rüstung werden Charaktere zu gemächlichen, teils fast statischen Akteuren im Kampf, weshalb die Trefferschwelle hier weder von einer Beweglichkeitskonstante noch der [[Agilität]] beeinflusst wird. Durch die Dicke der Rüstung hat auch die eigene [[Konstitution]] keinen Einfluss mehr.
Die Trefferschwelle ergibt sich daher bei schwerer Rüstung einfach aus der Summe der [[Ausstattung#Robustheit|Robustheitswerte]] aller getragenen [[Ausstattung]].
