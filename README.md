# Advanced networking labo's

Deze repository bevat alle oefeningen en labo's voor het Advanced netwerken boek. 

In de `labs` map vind je voor elk hoofdstuk oefeningen. Deze zijn bedoeld om je meer inzicht te geven in de behandelde materie.

Voor deze oefeningen ga je gebruik maken van een netwerk simulator. GNS3 (Graphical Network simulator 3) is een gratis network simulator. Dit houdt in dat je met deze tool op je computer een netwerk kan bouwen en dit doet zich voor als een echt netwerk. Zo kan je een virtueel netwerk labo bouwen doorheen het boek.

Indien je dit wenst kan je ook gebruik maken van een fysieke opstelling of een andere netwerk simulator. Alle labo's hebben een startup config. Deze kan je gebruiken om je toestellen in te stellen

# Installatie van GNS3
Hoe je GNS3 moet installeren en configureren vind je terug in de [installatie gids](https://github.com/epiecs/basic-networking-labs/blob/master/installation/gns3.md). 

De gids heeft zowel instructies voor VmWare workstation en Virtualbox.

## Nodige software en images

Bijna alle images van toestellen die we gebruiken in GNS3 zijn gratis te verkrijgen. Een uitzondering zijn de routers en switches. Voor de routers en switches gaan we gebruik maken van de `Cisco IOSv`, `IOSvL2` en `NX-OSv 9000` images. 

De volgende specifieke images zijn gebruikt:

```
Network devices
Switch - vios_l2-adventerprisek9-m.ssa.high_iron_20200929.qcow2
Router - vios-adventerprisek9-m.spa.159-3.m3.qcow2
Nexus  - nexus9500v64.10.1.1.qcow2

Guests
VPCS
Toolbox
```

Deze kan je verkrijgen als je een Cisco CML licentie aankoopt. Je kan de nodige info hier vinden: https://www.cisco.com/c/en/us/products/cloud-systems-management/modeling-labs

## Labo's

-   02 - Spanning tree configureren
    - [Lab-02-01](labs/hoofdstuk-02/lab-02-01/lab-02-01.md)
-   04 - Layer 2 redundancy configureren
    - [Lab-04-01](labs/hoofdstuk-04/lab-04-01/lab-04-01.md)
-   07 - IPv6 configureren
    - [Lab-07-01](labs/hoofdstuk-07/lab-07-01/lab-07-01.md)
-   10 - OSPF configureren
    - [Lab-10-01](labs/hoofdstuk-10/lab-10-01/lab-10-01.md)
-   12 - ACLS configureren
    - [Lab-12-01](labs/hoofdstuk-12/lab-12-01/lab-12-01.md)
-   14 - BGP configureren
    - [Lab-14-01](labs/hoofdstuk-14/lab-14-01/lab-14-01.md)
