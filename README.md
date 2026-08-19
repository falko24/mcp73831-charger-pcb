readme_content = """# Ładowarka akumulatorów Li-Po USB-C (MCP73831)

Kompaktowa, jednocelowa płytka zarządzania i ładowania akumulatorów Li-Ion/Li-Po zaprojektowana od zera w programie KiCad. Projekt opiera się na popularnym układzie liniowej kontroli ładowania **MCP73831** oraz wykorzystuje nowoczesne gniazdo zasilania **USB typu C**.

## 📸 Podgląd Płytki (PCB)

| Przód (Top) | Tył (Bottom) |
| :---: | :---: |
| ![Przód płytki](docs/pcb_front.png) | ![Tył płytki](docs/pcb_back.png) |

## 🚀 Funkcje
* **Złącze USB-C:** Skonfigurowane z odpowiednimi rezystorami ściągającymi na liniach CC dla standardowej negocjacji zasilania.
* **Inteligentne ładowanie:** Układ MCP73831 firmy Microchip zapewnia bezpieczny, regulowany cykl ładowania dla jednocelowych akumulatorów litowych.
* **Sygnalizacja stanu:** Wbudowana wskaźnikowa dioda LED do monitorowania procesu ładowania.
* **Kompaktowy rozmiar:** Czysty routing i zoptymalizowany układ ścieżek dostosowany do celów hobbystycznych oraz edukacyjnych.

## 🛠️ Narzędzia i Technologie
* **Oprogramowanie EDA:** KiCad (Edytor schematów i płytek PCB)
* **Kluczowe komponenty:**
  * `MCP73831` (Kontroler ładowania Li-Ion/Li-Po w obudowie SOT-23-5)
  * Gniazdo **USB-C** (interfejs 14-pinowy)
  * Standardowe elementy bierne do montażu powierzchniowego (SMD)

## 📂 Struktura Repozytorium
```text
├── 📁 docs/              # Dokumentacja graficzna (zdjęcia płytki)
├── 📁 gerbers/           # Gotowe pliki produkcyjne Gerber i wiercenia
├── 📁 schematics/        # Pliki schematów KiCad (.kicad_sch)
├── 📁 pcb/               # Pliki projektu płytki PCB (.kicad_pcb)
└── README.md             # Dokumentacja projektu
