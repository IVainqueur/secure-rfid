# Secure-RFID
In this repo, we implement a security system with RFID cards and python. 

in v1, the python "backend" has a `tags.txt` file that has all the Card IDs that are allowed into the system.

in v2, we want to integrate `sqlite` instead of a text file.

## Structure
```txt
src
├── arduino
│   └── index.ino
└── python
    ├── v1 # --- uses text file as database
    │   ├── index.py
    │   └── tags.sample.txt
    └── v2 # will use sqlite as database
```

## Contributors
- [ISHIMWE Vainqueur](https://github.com/IVainqueur)
- [Gakuba Edmond](https://github.com/edmondgaks)
- [Manzi Cedrick](https://github.com/manzicedrick)
- [Ndayishimiye Gilbert](https://github.com/nday-gilbert)
- [UMUTONI Mireille](https://github.com/umutunomireille)

