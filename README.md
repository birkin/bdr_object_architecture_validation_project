# readme for bdr-object-architecture-validation project

code and data for developing the bdr-object-architecture-validation project

on this page
- [plan](#plan)
- [small collections](#small-collections)
- [large collections](#large-collections)

---


## plan

- √ find, or remake that list of 10 small-collections (5-50)
- √ make another list of 10-large collections (over 500)
- √ diff the non-logged in, and logged-in, item-api output to better understand differences
    - examine items in the first, fifth, and tenth collections of the small and large list
        - small-1, bdr:b83dh3x8('Bactrian Camel Brain Imaging') -- identical
        - small-5, bdr:4hd866bq ('Brown University Library Innovation Prize') -- identical
        - small-12, bdr:vfja779p ('Development Studies') -- identical
        - large-1, bdr:bwehb8b8 ('Brown University Open Data Collection') -- identical
        - large-5, bdr:10855 ('John Carter Brown Library') -- identical when keys are sorted
        - large-10, bdr:7jw67xk5 ('The Brown Journal of World Affairs') -- identical
- get a item-api json example for each collection (two, if the object-architectures are different)
- feed those json-examples into the 'project'
- define initial limited clear goals for the spreadsheet
	- that the non-human fields can be used to create yaml-specifications
	- that those yaml-specifications can be used -- pre-ingest -- to validate submitted source-files (initially eg MODS and PDF)
	- that those yaml-specifications can be used -- post-ingest -- to validate that the ingested item meets the architectural specifications.
- make code to use the yaml-specifications to validate submitted source-files (initially eg MODS and PDF)
- make code to use the yaml-specifications to validate that the ingested item meets the architectural specifications.

---

## questions & insights

Q: does the public bdr-item-api show the same results whether the user is logged in or not?
A: yes

Q: can one tell, from the bdr-item-api, what will be shown in the "Files" sidebar in the "studio" view?
A: TODO

---
---


## small collections

small collections (5-50)

```
bdr:b83dh3x8 ('Bactrian Camel Brain Imaging') has 16 items
bdr:z7uxp2s2 ('Biology and Medicine') has 7 items
bdr:9d2cf9ga ('Brown Science Cartoons (SciToons)') has 22 items
bdr:sfaetyup ('Brown University Library Cuneiforms') has 28 items
bdr:4hd866bq ('Brown University Library Innovation Prize') has 9 items
bdr:yjdcnuc7 ('Brown University Student Publications') has 27 items
bdr:djmenxjt ('Brown University Superfund Research Program Digital Archive') has 8 items
bdr:a85tvjmj ('Cognitive, Linguistic, and Psychological Sciences') has 5 items
bdr:hsc574zv ('CreatureCast Archives') has 23 items
IGNORE (only contains subcollections) -- bdr:szurbkxj ('Data Science Initiative') has 8 items
IGNORE (only contains subcollections) -- bdr:qbdr7pht ('Data from "Synergid calcium ion oscillations define a new feature of pollen tube reception critical for blocking interspecific hybridization"') has 12 items
bdr:vfja779p ('Development Studies') has 6 items
bdr:h4drtury ('Distributed Gallery') has 21 items
bdr:7qpbz3jc ('EQUiSat Digital Archive') has 11 items
bdr:5dj99dxk ('Engineering') has 5 items
bdr:8mcg9ce3 ('Global Health Research Day') has 21 items
bdr:rxyb745r ('Grassroots Archive Digital Initiative') has 17 items
bdr:7y5xaxaq ('Haffenreffer Museum of Anthropology') has 19 items
bdr:318398 ('History') has 5 items
bdr:eh9gz9pb ('I-Team UTRAs: Interdisciplinary Team Undergraduate Teaching and Research Awards') has 33 items
bdr:59zu4v8a ('Ibis Mummy CT Imaging') has 7 items
```

---

## large collections

large collections (over 500)

```
bdr:bwehb8b8 ('Brown University Open Data Collection') has 903 items
bdr:16422 ('Catskills Institute') has 1375 items
bdr:10870 ('David Winton Bell Gallery') has 6805 items
bdr:26140 ('Hurricane Katrina Archive') has 1105 items
bdr:10855 ('John Carter Brown Library') has 10030 items
bdr:t4zanxgh ('Joukowsky Institute Collection') has 2159 items
bdr:6z7c3a7f ('Pembroke Record') has 1586 items
bdr:gm3nagwz ('Summer Research Symposium') has 580 items
bdr:26151 ('Technology: Material Culture in the Built Environment') has 612 items
bdr:7jw67xk5 ('The Brown Journal of World Affairs') has 1134 items
bdr:ejc2sud7 ('Warren Alpert Medical School Academic Symposium') has 636 items
bdr:bwehb8b8 ('Brown University Open Data Collection') has 903 items
bdr:16422 ('Catskills Institute') has 1375 items
bdr:10870 ('David Winton Bell Gallery') has 6805 items
```

---

[END]
