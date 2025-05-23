Hvis du ikke er på Github (for å lese denne filen): https://github.com/sivertmh/sysadm_fordypning

# Dokumentasjon av Teknisk Oppsett - Fordypning Systemadministrasjon

## Om Fordypningen

I denne fordypningen satt jeg opp et komplekst system. Jeg brukte Active Directory som et utgangspunkt og lagde en virtuell maskin på HP mini-PC med operativsystemet Windows Server 2022 og installerte ADDS, samt DNS server. AD blir brukt til å ha kontroll over et domene, som i praktiske situasjoner pleier å være en arbeidsplass, noe jeg forsøkte å simulere med denne fordypningen. For å kontrollere fiktive arbeidere med AD måtte jeg ha en klientmaskin som var del av AD-domenet, eller forest-en, sivertserverdomain.local. Til dette laget jeg enda en virtuell maskin på HP mini-PC

## Utstyret jeg brukte

### Fysisk tstyr

_Jeg brukte til slutt dettte:_

HP 260 G3 DM Business mini-PC (8GB RAM)

Tp-link Archer C50 ruter

Nettverkskabel (koblet HP mini-PC til ruter)

Lenovo Thinkpad T15 (skole-PC for RDP)

### Programvare

_Virtuelle Maskiner:_

Windows Server 2022 (VM WinServer22)

Windows 10 Education Enterprise (VM Win10Klient)

_Annet:_

Active Directory Server
