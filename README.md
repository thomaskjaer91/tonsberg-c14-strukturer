# Struktur- og C14-data fra middelalderbyen Tønsberg
## Beskrivelse
Disse datasettene utgjør grunnlaget for analysen gjennomført i masteroppgaven *Produksjonen av en by. En bymorfologisk studie av Tønsberg i middelalderen*. 

## Innhold
- `C14-database_Tonsberg_v1.0.csv` – C14-datasett i CSV UTF-8 format.
- `C14-database_Tonsberg_v1.0.xlsx` – Formatert C14-datasett i Excel-format.
- `Struktur-database_Tonsberg_v1.0.csv` – Strukturdatabase i CSV UTF-8 format.
- `Struktur-database_Tonsberg_v1.0.gpkg` – Strukturdatabase i geopackage format.

## Metadata - strukturdatabase

| **Variabel** | **Beskrivelse** |
| :--- | :--- |
| **WKT** | Strukturenes geometri (MULTIPOLYGON). |
| **fid** | Intern unik identifikator opprettet av QGIS. |
| **sone** | Analyseområder definert i masteroppgaven.|
| **lokalitet** | Navn på utgravningslokaliteten eller gateadresse.|
| **struktur_id** | Unik identifikator for den arkeologiske strukturen. |
| **struktur_navn** | Navn gitt til strukturen i utgravningsrapporten. |
| **funksjonskode** | Numerisk kode som beskriver både byverdi og bruksverdi. |
| **byverdi** | Funksjonell kategorisering som er nærmere beskrevet i masteroppgaven. |
| **bruksverdi** | Overordnet funksjonskategori. |
| **areal_m2** | Spesifikk funksjonskategori. |
| **ET_1 til ET_6** | Binær datering (1/0) for analyseperiodene benyttet i masteroppgaven.ET1:600–1100, ET2:1100–1200, ET3:1200–1300, ET4:1300–1400, ET5:1400–1500, ET6:1500–1537. |
| **utgravningsfase** | Faseangivelse fra utgravningsrapport. |
| **utgravningsfase_fra** | Antatt nedre datering for fasen. |
| **utgravningsfase_til** | Antatt øvre datering for fasen. |
| **C14_samlet** | Gjennomsnittet av den kalibrerte median-dateringen gitt av OxCal. |
| **C14_labid_1 til 4** | Laboratoriereferanser for dateringer tilknyttet strukturen. |
| **utgravd_år** | Året det arkeologiske feltarbeidet ble utført. |
| **utgravd_år** | Institusjon ansvarlig for utgravningen. |
| **utgravd_areal** | Utgravningsfeltets størrelse. |
| **tbg_kode** | Prosjektkode brukt av Riksantikvaren. |
| **niku_prosjektnr** | Prosjektkode brukt av NIKU. |
| **c_nr** | Katalognummer. |
| **kilde** | Referanse til utgravningsrapporten. |

### Koordinatsystem og nøyaktighet
* **Koordinatsystem:** ETRS89 / UTM sone 32N (EPSG:25832)  
* **Nøyaktighet:** Strukturene er manuelt georeferert i QGIS med utgangspunkt i originale fasekart og illustrasjoner fra utgravningsrapportene.

## Metadata - C14-datasett

| **Variabel** | **Beskrivelse** |
|---------------|-----------------|
| **RadID** | Identifikasjonsnummer for hver oppføring.|
| **Lokalitet** | Navn på utgravningslokaliteten eller gateadresse.|
| **PrøveID** | Innmålingsnummer ved innsamling av prøven i felt.|
| **KontekstID** | Strukturen/laget prøven er hentet fra/tilknyttet.|
| **Kontekst-beskrivelse** | Kort beskrivelse av konteksten til den innsamlede prøven.|
| **LabID** | Laboratoriets referansenummer for dateringen. |
| **14C-BP** | Radiokarbonalder oppgitt i år før nåtid (BP) med standardavvik. |
| **Kalibrert alder (2 sigma)** | Dateringsintervall i fvt./evt. med 95.4% sannsynlighet. Kalibrert i januar 2026 med IntCal20 i OxCal v4.4.|
| **Delta 13C** | Normalsiert forhold mellom de stabile karbonisotopene 12C og 13C. Oppgitt der data er tilgjengelig. |
| **Øst_UTM32_ETRS89** | X-koordinat (Øst/Easting).|
| **Nord_UTM32_ETRS89** | Y-koordinat (Nord/Northing).|
| **Referanse** | Referanse til utgravningsrapport eller annen relevant publikasjon.|

### Koordinatsystem
ETRS89 / UTM sone 32N (EPSG:25832)  

## Hvordan sitere
Kjær, Thomas (2026). *Struktur- og C14-data fra middelalderbyen Tønsberg*. Zenodo. DOI: 

## Lisens
Datasettene er publisert under **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.
Du står fritt til å bruke, dele og tilpasse materialet så lenge du oppgir korrekt kildehenvisning.

## Kontakt
**Forfatter:** Thomas Kjær  
**Epost:** tkarlbergkjaer@gmail.com
**Forfatter_ORCID:** [https://orcid.org/0009-0001-5858-4112](https://orcid.org/0009-0001-5858-4112)
