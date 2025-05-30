```mermaid
---
displayMode: compact
---
%%{init: { 'gantt': {'leftPadding': 110, 'barHeight': 30} } }%%
gantt
    dateFormat  DD-MM-YYYY

    section PATRONATO<BR>SAN VINCENZO
        1° ANNO: 01-09-2019,31-05-2020, classPSV
        2° ANNO: 01-09-2020,31-05-2021, classPSV
        3° ANNO: 01-09-2021,31-05-2022, classPSV

    section QUALIFICA
        Qualifica 85/100 :milestone, 15-06-2022

    section PESENTI
        3° ANNO: 14-09-2022,08-06-2023, classPesenti
        4° ANNO: 14-09-2023,08-06-2024, classPesenti
        5° ANNO: 14-09-2024,08-06-2025, classPesenti

    section TORMEC SRL
        1° TIROCINIO: 21-03-2021,04-06-2021

    section MB MECCANICA SRL
        2° TIROCINIO: 19-09-2021,29-12-2021, classMB
        3° TIROCINIO: 20-03-2023,13-04-2023, classMB

    section PRSE SRL
        4° TIROCINIO: 26-02-2024,15-03-2024, classPRSE

    classDef classPSV fill:#e18139,stroke:#000,stroke-width:1px;
    classDef classPesenti fill:#305fa2,stroke:#000,stroke-width:1px;
    classDef classMB fill:#fd7a04,stroke:#000,stroke-width:1px;
    classDef classPRSE fill:#004f7d,stroke:#000,stroke-width:1px;
```