# printing-script-for-courant-cluster

This is a printing script used for printing files from Courant printers through Courant servers. A login is required before using this script.

---

Use `-p` flag to select printer on each floor. E.g.
```bash
./printfile -p mf-10 <filename-of-your-choice>
```

Use `-s` flag to configure single-sided printing. The default option is double-sided. E.g.
```bash
./printfile -s <filename-of-your-choice>
```
