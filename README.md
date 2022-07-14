# Introduksjon

En workshop som kan hjelpe deg i gang med å jobbe med data og innsikt. Workshopen gir deg en introduksjon til hovedområdene inne data og innsikt: Data Engineering, Data anlysis og Data Science.

## Hvordan komme igang

Workhopen består av et sett med oppgaver som løses i [Google Cloud Plattform](https://console.google.com) (GCP) og i Colab (notebooks). Det kreves tilgang til GCP for å kunne gjennomføre workshopen. Tilgangen gis til din Bekk-konto av en av kursholderne. For å kunne gi deg tilgang, må du først knytte Bekk-eposten din til en Google-konto. For å gjøre dette kan du følge denne guiden her: https://support.google.com/accounts/answer/27441?hl=en

> 💡 Det kan være lurt å gjøre dette i en privat fane i tilfelle du allerede er logget inn med en annen Google-konto.

Når du har knyttet Bekk-eposten din til en Google-konto kan du:

-   Gi beskjed til kursholderne slik at de kan gi deg tilgang til prosjektet.

-   Logg deretter inn på [GCP](https://console.cloud.google.com/) med din Bekk e-post. Prosjektet vi skal jobbe i heter `data-intro`.

I Colab vil vi skrive kode i Python og benytte oss av en pakke som heter pandas (https://pandas.pydata.org/). Pandas er et open spurce verktøy som fungerer utmerket når man skal jobbe med data og analyse.

## Oppgaver

Oppgavene benytter seg av to datasett - [Oslo bysykkel](https://oslobysykkel.no/apne-data/historisk) og et subsett av værdata i Oslo fra [meteorologisk institutt](https://frost.met.no/index.html). For enkelhets skyld er Datasettene allerede hentet ut fra kildene og lagret i vårt GCP-prosjekt.

### Bruk av oppgavesettene

Colab fungerer ikke veldig bra til å redigere/kjøre kode samtidig med andre brukere. Du må derfor **lage en egen kopi av oppgavesettene** og lagre disse til din Drive. Slik lager du en kopi:

1. Åpne oppgavesettet du skal løse
2. Velg _file_ og så "Save a copy in drive"
3. Vent litt mens Colab jobber 😎
4. Velg "open in new tab"
5. Lukk den forrige fanen
6. Løs oppgavene 🏆

### Oppbygning

Workshopen består av to deler, hvor del 1 har hovedfokus på data engineering, mens del 2 fokuserer mer på data analysis og data science.

I del 1 vil du lære hvordan man setter opp en enkel data pipeline, dvs hvordan man flytter og klargjør data for videre analyse i verktøy som er bedre egnet til dette. I del 2 ser vi videre på inneholdet i datasettene og undersøker hva vi kan få ut av datagrunnlaget.
//todo formuler setningen over bedre beskrivelse av del 2

Oppgavene for del 1 finner du her
https://colab.research.google.com/drive/1-QEBz-C3tvWlPocO-9PIq1_HMl6b25z-?usp=sharing

Oppgavene for del 2 finner du her
https://colab.research.google.com/drive/1YrQ4VXrjqQIUd-iSEjmbRtHnMVMm-AIU?usp=sharing
