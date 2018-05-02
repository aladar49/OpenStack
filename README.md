OpenStack: Heat automatizálás házi feladat
Felhő alapú hálózatok

Készítsünk Heat sabont amely egy alább részletezett hálózattal egy Wordpress szervert installál+konfigurál+elindít.
A kialakítandó hálózat a heat konfigurációs fájl segítségével:
- hozzunk létre egy saját belső/privát hálózatot+alhálózatot a wordpress VM ehhez kapcsolódjon
- a belső/privát hálózaton legyen beállítva DNS szerver (pl. publikus Google DNS 8.8.8.8)!
- hozzunk létre egy routert, ami ehhez a belső/privát hálózathoz kapcsolódik
- ezen a routeren keresztül kapcsolódjunk a külső hálózathoz (már létező ‘ext-net’)
- a VM kapjon floating IP-t
- engedélyezzük a security group beállításoknál a web, ssh, ping kapcsolatokat
