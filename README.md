# Wikidata @ arise_hack2022

## Linking Nederlandse Soortenregister in Wikidata

```mermaid
  graph TD;
      NS[Nederlands Soortenregister]==>|Trixidata notebook|WD[Wikidata];
      WD==>|Trixidata notebook|WP[Wikipedia];
      G[Gbif]-->WD;
      I[iNaturalist]-->WD;
      DOI[Literature]-->WD;
      ORCID[Person]-->WD;
      WD-->EE[Entity Explosion]
```

## Linking collections with collectors from the carribean through Wikidata
```mermaid
  graph TD;
      NS[Nederlands Soortenregister]<==>WD[Wikidata];
      B[Binomia]<==>WD;
```

## What do green iguana eet



## Birdsounds in Wikidata
```mermaid
  graph TD;
      XC[Xeno Canto]<==>WD[Wikidata];
      XC[Xeno Canto]<==>WD[Wikimedia Commons];
      WC <==> WD;
```
