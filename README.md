# arise_hack2022

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
