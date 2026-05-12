---
title: "Nasjonalt grunnkart for arealanalyse (Testversjon 2)"
updated: "2026-02-16"
organization: "Statistisk sentralbyrå"
logo: "https://register.geonorge.no/data/organizations/971526920_SSB_liten.png"
---

# Produktspesifikasjon: Nasjonalt grunnkart for arealanalyse (Testversjon 2)

## Generelt om spesifikasjonen


### Unik identifisering

28c28e3a-d88f-4a34-8c60-5efe6d56a44d

#### Fullstendig navn

Nasjonalt grunnkart for arealanalyse (Testversjon 2)

#### Versjon

2024-02-13

### Referansedato

2025-06-30

### Ansvarlig organisasjon

Statistisk sentralbyrå

### Språk

nor

### Hovedtema

Grunnkart, Arealregnskap, Arealstatistikk, Økosystemtyper, Arealanalyse, Testversjon 2, ØkologiskGrunnkart, Det offentlige kartgrunnlaget, geodataloven, arealplanerPBL, Plan

### Sammendrag

Nasjonalt grunnkart for arealanalyse er tilgjengelig som Testversjon 2. 

**Dersom du ønsker å se på Årsversjon 2025 av Grunnkartet, er den nye WMS-tjenesten tilgjengelig.** Mer informasjon om WMS-tjenesten finner du på <https://kartkatalog.geonorge.no/Metadata/c7dc425b-60cd-42f7-a84e-202c7d7b912a>. 

- - -
**Oppdateringer og feilretting!** 

Nye filer ble publisert 30. juni (ca. klokka 1500). Det er rettet opp i topologifeil, men det gjenstår noen feil i enkelte kommuner og fylker i enkelte projeksjoner og formater. De berørte kommunene og fylkene gjengitt med fylkes- og kommunenummer er:  

* UTM GML: 46, 50, 55, 56, 1806,1815, 4642, 4644

- UTM FGDB: 18, 40, 46, 50, 55, 56

+ Geografisk (ETRS89) GML: 33, 42, 46, 50, 55, 56, 4642, 4644, 5056

- Geografisk (ETRS89) FGDB: 40, 50, 55, 56, 5060

Disse filene vil dessverre ikke bli rettet før årsversjonen publiseres. Feilen som har oppstått kan føre til utfordringer ved geometrisk prosessering. De fleste GIS-programmer har funksjonalitet for å reparere slike topologifeil, og brukere som ønsker å ta datasettet i bruk før en fullstendig rettet versjon er tilgjengelig, oppfordres til å benytte disse verktøyene. Vi beklager ulempen!

- - -

Grunnkartet er utviklet i samarbeid mellom NIBIO, SSB, Kartverket og Miljødirektoratet, og er ment som et felles datagrunnlag for ulike typer arealanalyser.

Datasettet bygger på eksisterende data fra det offentlige kartgrunnlaget (DOK), som viser arealressurs- og arealbruksdata, og innebærer ingen nykartlegging.  Kildedata som er brukt i denne versjonen var oppdatert per 01.01.2024. I tillegg til arealressurs- og arealbruksdata er det lagt inn økosysteminformasjon i henhold til Eurostats klassifikasjonssystem. Grunnkartet kan kobles med andre datakilder, som for eksempel arealplaner, og benyttes som grunnlag for ulike typer arealanalyser og arealregnskap. Les mer om datainnhold og metode under Prosesshistorie.


**Rapporter**


* Alle endringer som er implementert i Årsversjon 2025 er samlet i rapporten [Nasjonalt grunnkart for arealanalyse - Årsversjon 2025](https://doi.org/10.21350/4m2k-7z04)

* Alle tilbakemeldinger til Testversjon 2 er samlet i rapporten [Nasjonalt grunnkart for arealanalyse, Testversjon 2 - Tilbakemeldinger og vurderinger](https://www.kartverket.no/globalassets/forskning-og-utvikling/rapporter/nasjonalt-grunnkart-for-arealanalyse-testversjon-2-tilbakemeldinger-og-vurderinger.pdf).

* Alle endringer som er implementert i Testversjon 2 er samlet i rapporten [Testversjon 2 - Nasjonalt grunnkart for bruk i arealregnskap](https://hdl.handle.net/11250/3185743)

* Alle tilbakemeldinger til Testversjon 1 er samlet i rapporten [Grunnkart for bruk i arealregnskap - Tilbakemeldinger, vurderinger og anbefalinger](https://www.kartverket.no/globalassets/forskning-og-utvikling/rapporter/rapport-grunnkart-for-bruk-i-arealregnskap-tilbakemeldinger-vurderinger-og-anbefalinger-2.pdf).

* Les mer om metode og bruk av Grunnkartet i rapporten [Grunnkart for bruk i arealregnskap](https://hdl.handle.net/11250/3120510)

### Formål

Nasjonalt grunnkart for arealanalyse er en sammenstilling av grunnleggende datasett som danner basis for ulike typer arealregnskap. Formålet er å tilrettelegge data for kommunal og regional forvaltning, slik at blant annet kostnadskrevende dobbeltarbeid unngås. Et felles kartgrunnlag gjør det også enklere å sammenligne arealregnskap på tvers av sektorer. Dette gir kommuner og fylker, sammen med rådgivende firmaer, mulighet til å fokusere på å tilrettelegge supplerende temadata for å lage sektorspesifikke regnskap.

## Spesifikasjonsomfang

**Nivå**:
#### filnedlastning
<beskrivelse>

**Utstrekning**:

- **tidsmessig**: - **intervall**: - 2024-02-13, 2025-06-30

**Juridiske begrensninger**:

- **Tilgangsbegrensninger**: Norge digitalt begrenset
- **Bruksbegrensninger**: Lisens
- **Lisens**: No conditions apply to access and use
- **Lisenslenke**: <http://inspire.ec.europa.eu/metadata-codelist/ConditionsApplyingToAccessAndUse/noConditionsApply>

## Innhold og struktur

**Bruk**:
Grunnkartet kan testes som grunnlag for etablering av arealregnskap, og kan suppleres med spesifikke data tilpasset ulike regnskapsformål, slik som kommuneplaner, miljødata eller jordegenskaper. 

Kommunal- og distriktsdepartementet (KDD) publiserte i 2023 en veileder for arealregnskap i kommunene (https://www.regjeringen.no/no/dokumenter/arealregnskap-i-kommuneplan/id3017913/), som gir oversikt over relevante datakilder og metoder. Når en endelig årsversjon av Grunnkartet er klart til drift, vil det kunne supplere og delvis erstatte datakildene som er nevnt i denne veilederen. For andre typer arealregnskap må det utvikles egne metoder med tilhørende veiledere.

### Datamodell - filnedlastning



[Objektkatalog - filnedlastning](filnedlastning/objektkatalog.html)



<a href="filnedlastning/filnedlastning_feature_catalogue.png" title="Klikk for stor visning"><img src="filnedlastning/filnedlastning_feature_catalogue.png" alt="Datamodell filnedlastning" style="max-width: 100%; height: auto;" /></a>

## Referansesystem

**Romlige referansesystemer**:

- **kode**: EPSG:25832
  **navn**: EUREF89 UTM sone 32, 2d

- **kode**: EPSG:25833
  **navn**: EUREF89 UTM sone 33, 2d

- **kode**: EPSG:25835
  **navn**: EUREF89 UTM sone 35, 2d

- **kode**: EPSG:4258
  **navn**: EUREF 89 Geografisk (ETRS 89) 2d

- **kode**: EPSG:25832
  **navn**: EUREF89 UTM sone 32, 2d

**Romlig representasjonstype**: Vektor

## Kvalitet

**Nivå**: dataset

- **navn**: Prosentvis oppfyllelse av FAIR-prinsipper
  **Måleparameter**: Angir fullstendighet i forhold til krav fra FAIR-prinsippene (The FAIR Guiding Principles for scientific data management and stewardship)
  **Resultat**: 83

- **navn**: FAIR
  **Resultat**: Prosentvis oppfyllelse av FAIR-prinsipper: 83%

**Beskrivelse**:
Grunnkartet kan lastes ned kommunevis for Norge digitalt-parter. WMS-tjenesten er åpen og kan benyttes for innsyn av alle.

Vi vil veldig gjerne høre hva du mener om Testversjon 2 av Grunnkartet - send oss gjerne en e-post. 
Alle samarbeidspartene i prosjektet kan kontaktes ved tilbakemeldinger og/eller spørsmål. 

For generelle spørsmål og spørsmål til metode: gisdrift@nibio.no

For spørsmål knyttet til Arealbruk: margrete.steinnes@ssb.no

For spørsmål knyttet til Arealdekke: gisdrift@nibio.no

For spørsmål knyttet til Økosystemtype: ellen.arneberg@miljodir.no

## Datavedlikehold

**Vedlikeholdsfrekvens**: Årlig

**Vedlikeholdsnotat**:
Grunnkartet kan testes som grunnlag for etablering av arealregnskap, og kan suppleres med spesifikke data tilpasset ulike regnskapsformål, slik som kommuneplaner, miljødata eller jordegenskaper. 

Kommunal- og distriktsdepartementet (KDD) publiserte i 2023 en veileder for arealregnskap i kommunene (https://www.regjeringen.no/no/dokumenter/arealregnskap-i-kommuneplan/id3017913/), som gir oversikt over relevante datakilder og metoder. Når en endelig årsversjon av Grunnkartet er klart til drift, vil det kunne supplere og delvis erstatte datakildene som er nevnt i denne veilederen. For andre typer arealregnskap må det utvikles egne metoder med tilhørende veiledere.

**Status**: Under arbeid

**dataAcquisitionAndProcessing**:

- **processStep**:
  - **description**:
    Arbeidet med Nasjonalt grunnkart for arealanalyse startet i 2023 som et samarbeid mellom NIBIO, SSB, Kartverket og Miljødirektoratet. Arbeidet med å etablere Grunnkartet tok utgangspunkt i metoder og datagrunnlag som allerede benyttes i arbeidet med den offentlige arealbruks- og arealressursstatistikken. Dette grunnlaget er ytterligere beriket ved å tilføre data fra andre offentlige kartdatabaser og registre, samt tilføre datasettet en økosystemkoding. 

    *Testversjon 1* av Grunnkartet ble publisert i februar 2024. Våren 2024 ble det gjennomført brukerdialog gjennom møter med utvalgte brukere og spørreskjemaer. Tilbakemeldingene pekte på behov for retting av topologifeil, tematiske avklaringer og bedre brukerveiledning. 

    Testversjon 1 inneholdt følgende egenskaper: Arealdekke, Arealbruk, Økosystemklasse, Grøntandel, Areal og Kommunenummer.

    I arbeidet med *Testversjon 2* har fokuset vært å lage et mer ryddig, enklere og mer intuitivt kart. Det er blant annet arbeidet med tematiske problemstillinger rundt nomenklaturen for arealdekke og arealbruk, og det er foretatt en mer systematisk topologi- og geometrirydding. I tillegg er det inkludert arealbruk i hav. Testversjon 2 ble publisert 1. april 2025, og inkluderer forbedringer basert på tilbakemeldingene etter Testversjon 1. 

    Ny periode med brukerinvolvering ble gjennomført våren 2025. Innspillene vurderes og eventuelle endringer implementeres frem mot en standardisert årsversjon, som er planlagt publisert i desember 2025. Målet er at Grunnkartet skal oppdateres årlig, og videreutvikles og forvaltes innenfor rammene av det nasjonale geodatasamarbeidet.

    Testversjon 2 inneholder følgende egenskaper: Arealdekke, Arealbruk, Økosystemklasse, Areal, Kommunenummer, Kilde, Treslag, Grunnforhold og Arealbruk i hav (stedfast og ikke-stedfast). 

    - - - 
    Tematiske detaljer

    **Arealdekke** baseres på klassifikasjonen av arealressurs i FKB-AR5, med tilleggsinformasjon om skog og snaumark. I Testversjon 2 er dette temaet oppdelt i fire temalag; arealdekke, treslag, skogbonitet og grunnforhold. Kodingen skal være gjenkjennbar for brukere som kjenner AR5-typologien, men med noen avvik og endringer. 

    Arealbruksklassifikasjonen baseres på SSB-arealbruk, slik den er tilgjengelig på Geonorge. En grov inndeling av arealbruken på land er gitt i arealbruk_hovedklasse, mens en mer fininndelt klassifisering finnes i arealbruk_underklasse.  Nytt i testversjon 2 er at kildedata for hvert polygon er inkludert, noe som kan gi bedre innsikt i datakvalitet og gjør det enklere å spore og rette feil. Arealbruk er gitt for bebygde og opparbeida arealer, men for ubebygde områder vil disse kolonnene være blanke.

    Arealbruk i hav er nytt i Testversjon 2, og vises i to kolonner. HavArealbrukStedbundet viser installasjoner, og annen klart stedbundet aktivitet, mens HavFiskeriBruk viser områder der det foregår fiske. De to kolonnene kan ansees som en smakebit på hvordan arealbruk i hav kan framstilles, og det vil være viktig å få brukernes tilbakemeldinger på disse. 

    Økosystemklassifikasjonen følger, så langt det er mulig, Eurostats anbefalte klassifikasjon (3 nivåer). I bebygde områder følges den til nivå 3 så langt det har latt seg gjøre. Miljødirektoratet, med bistand fra NINA, har tilordnet Eurostat-klasser til kombinasjoner av arealdekke, arealbruk, treslag, grunnforhold, bonitet og kysttilhørighet. Som hovedregel overstyrer arealbruk arealdekke ved konflikt.

    Eurostats økosystemklassifikasjon er beskrevet i [NIBIO rapport 9 (143) 2023 Hovedøkosystemkart for Norge](https://hdl.handle.net/11250/3106442)
    - - -

## Presentasjon

**Tegnforklaring**:
<https://register.geonorge.no/tegneregler/grunnkart-for-arealregnskap-testversjon-2>

## Leveranse

**Distribusjoner**:

- **format**: - **format**: GEONORGE:DOWNLOAD
  **tilgang**:

  - **lenke**: <https://nedlasting.geonorge.no/api/capabilities/>
  - **protokoll**: GEONORGE:DOWNLOAD

- **tittel**: Geonorge nedlastning
  **format**: - **format**: Geonorge nedlastning
  **tilgang**:

  - **lenke**: <https://nedlasting.geonorge.no/api/capabilities/>
  - **protokoll**: GEONORGE:DOWNLOAD

- **tittel**: Nasjonalt grunnkart for arealanalyse WMS - årsversjon 2025
  **format**: - **format**: OGC WMS
  **tilgang**:

  - **lenke**: <https://wms.nibio.no/cgi-bin/grunnkart_arealanalyse?service=WMS&request=GetCapabilities>
  - **protokoll**: WMS-tjeneste
  - **Lisens**: Åpne data
  **Notater**: Tjeneste

## Metadata

**Standard**: ISO19115

**Standardversjon**: 2003

**Metadatadato**: 2026-02-16

**språk**: nor

**Kontaktpunkt**:

- **organisasjon**: Norsk institutt for bioøkonomi
- **epost**: post@kartverket.no
- **rolle**: pointOfContact

**Identifikatorer**:

- **Utsteder**: geonorge
  **kode**: 28c28e3a-d88f-4a34-8c60-5efe6d56a44d

**Metadatalenke**:
<https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=28c28e3a-d88f-4a34-8c60-5efe6d56a44d>
