# Date de contact ale instituțiilor publice din România

Seturi de date deschise cu datele de contact oficiale ale instituțiilor publice din România, pe județe: case de pensii, case de asigurări de sănătate, comisariate pentru protecția consumatorilor, servicii de permise și înmatriculări, servicii de pașapoarte, agenții de ocupare a forței de muncă, agenții ARR, ghișee de stare civilă, autogări licențiate și operatori de distribuție a energiei electrice.

Datele sunt întreținute de redacția [PunctContact](https://punctcontact.ro/) și publicate și pe [punctcontact.ro/date-publice/](https://punctcontact.ro/date-publice/).

## Ce conține

| Set | Rânduri | Fișiere | Pe site |
|---|---|---|---|
| [Autogări licențiate din România](date/autogari/) | 226 | `date/autogari/punctcontact-autogari.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/autogari/) |
| [Ghișee de stare civilă și evidența persoanelor](date/stare-civila/) | 691 | `date/stare-civila/punctcontact-stare-civila.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/stare-civila/) |
| [Servicii publice de permise de conducere și înmatriculări](date/permise-inmatriculari/) | 42 | `date/permise-inmatriculari/punctcontact-permise-inmatriculari.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/permise-inmatriculari/) |
| [Servicii publice comunitare de pașapoarte](date/pasapoarte/) | 42 | `date/pasapoarte/punctcontact-pasapoarte.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/pasapoarte/) |
| [Case județene de pensii](date/case-de-pensii/) | 42 | `date/case-de-pensii/punctcontact-case-de-pensii.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/case-de-pensii/) |
| [Case județene de asigurări de sănătate](date/case-de-sanatate/) | 42 | `date/case-de-sanatate/punctcontact-case-de-sanatate.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/case-de-sanatate/) |
| [Comisariate județene pentru protecția consumatorilor](date/comisariate-anpc/) | 42 | `date/comisariate-anpc/punctcontact-comisariate-anpc.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/comisariate-anpc/) |
| [Agențiile teritoriale ale Autorității Rutiere Române](date/agentii-arr/) | 42 | `date/agentii-arr/punctcontact-agentii-arr.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/agentii-arr/) |
| [Agenții județene pentru ocuparea forței de muncă](date/agentii-ocupare-ajofm/) | 42 | `date/agentii-ocupare-ajofm/punctcontact-agentii-ocupare-ajofm.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/agentii-ocupare-ajofm/) |
| [Operatorii de distribuție a energiei electrice, pe județ](date/distributie-energie-electrica/) | 42 | `date/distributie-energie-electrica/punctcontact-distributie-energie-electrica.csv` · `.json` | [pagina setului](https://punctcontact.ro/date-publice/distributie-energie-electrica/) |

Fiecare rând are:
- **sursa_oficiala** — pagina instituției de pe care a fost citit;
- **verificat** — data la care a fost citit (format AAAA-LL-ZZ);
- **pagina_punctcontact** — fișa corespunzătoare, unde datele sunt prezentate și explicate.

## Cum sunt verificate datele

- Doar din surse oficiale: site-ul instituției sau al autorității care o coordonează.
- Fiecare valoare e citită de două ori, în două încărcări separate ale paginii oficiale.
- Când două pagini oficiale se contrazic (de exemplu două programe diferite), publicăm ambele variante și spunem asta.
- Nu publicăm nume de persoane, numere ale conducerii, compartimente interne, e-mailuri nominale sau date temporare.

Metodologia completă: [punctcontact.ro/metodologie/](https://punctcontact.ro/metodologie/).

## Format

- **CSV**: UTF-8 cu BOM, separator virgulă (RFC 4180). În Excel cu setări românești, folosiți *Date → Din text/CSV* și alegeți separatorul virgulă.
- **JSON**: aceleași câmpuri, plus metadate (licență, dată, sursă).

## Licență și citare

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ro). Puteți folosi, modifica și redistribui datele, inclusiv comercial, cu condiția atribuirii:

> Sursa: PunctContact — https://punctcontact.ro/date-publice/ (CC BY 4.0)

Vezi și `CITATION.cff`.

## Actualizări și corecturi

Seturile sunt regenerate la fiecare reverificare. O greșeală sau o schimbare la o instituție se poate semnala la contact@punctcontact.ro sau prin [pagina de contact](https://punctcontact.ro/contact/).

---

## English summary

Open datasets (CSV + JSON) with the official contact details of Romanian public institutions, per county: pension offices, health insurance offices, consumer protection offices, driving licence and vehicle registration services, passport services, employment agencies, road authority agencies, civil registry offices, licensed bus stations and electricity distribution operators. Every row carries the official source URL and the verification date. Licence: CC BY 4.0 — please credit "PunctContact — https://punctcontact.ro/date-publice/".
