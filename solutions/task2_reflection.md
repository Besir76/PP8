# Reflexion zu Task 2 – Parameter vs. Flags

## 1. Wie gibt man Dateinamen mit `-i` und `-o` an?
Dateinamen werden direkt nach dem jeweiligen Flag angegeben, zum Beispiel:
```bash
./programm -i input.txt -o output.txt
```
- `-i` steht für Eingabedatei
- `-o` steht für Ausgabedatei

---

## 2. Unterschied: Parameter vs. Flags

| Merkmal        | Flags (`-a`, `-b`)           | Parameter (`-n 42`, `-s hallo`)        |
|----------------|------------------------------|----------------------------------------|
| Bedeutung      | Ein-/Ausschalten einer Option | Übergabe eines Werts an das Programm |
| Wert enthalten | Nein                         | Ja                                     |
| Beispiel       | `-v` (verbose Modus aktiv)   | `-n 5` (Zahl 5 wird übergeben)         |

Kurz gesagt:
- **Flags**: Nur "an" oder "aus"
- **Parameter**: Geben Werte an

