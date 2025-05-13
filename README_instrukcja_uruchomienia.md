
# 📦 Formularz Katalogu Produktów — Instrukcja uruchomienia

Aplikacja webowa stworzona w **Streamlit** do zarządzania katalogiem produktów i załącznikami (rysunki, specyfikacje, schematy pakowania).

---

## ✅ Wymagania

- Python 3.8+
- Pakiety Python:
  - `streamlit`
  - `pandas`
  - `openpyxl`

---

## 🔧 Instalacja (Windows)

### 1. Zainstaluj Python

Pobierz instalator:  
👉 https://www.python.org/downloads/windows/

Podczas instalacji zaznacz opcję: **„Add Python to PATH”**

Zweryfikuj instalację:
```bash
python --version
```

---

### 2. Zainstaluj wymagane biblioteki

W terminalu / wierszu poleceń:
```bash
pip install streamlit pandas openpyxl
```

---

### 3. Pobierz plik aplikacji

Pobierz:  
👉 `app_final_hiperlink_upload_podglad.py`  
i umieść np. na Pulpicie lub w folderze `C:\projekty\formularz`

---

### 4. Uruchom aplikację

W terminalu:

```bash
cd C:\projekty\formularz
streamlit run app_final_hiperlink_upload_podglad.py
```

Aplikacja otworzy się automatycznie w przeglądarce:  
📍 http://localhost:8501

---

## 📁 Co robi aplikacja?

| Element                  | Działanie                                                            |
|--------------------------|----------------------------------------------------------------------|
| ✅ Dane produktu          | Trafiają do pliku `katalog_web.xlsx`                                 |
| 📂 Załączniki             | Zapisują się w folderze `uploads/`                                   |
| 🔗 Hiperłącza             | W Excelu pojawia się aktywna nazwa pliku jako hiperłącze             |
| 🧹 „Czyść formularz”      | Czyści dane — odśwież stronę (F5), by zacząć od nowa                 |
| 👀 „Podgląd zapisów”      | Wyświetla dane z Excela w dolnej części aplikacji                    |

---

## 📂 Struktura katalogu

```
formularz/
├── uploads/                   # Załączone pliki
├── katalog_web.xlsx          # Baza danych katalogu produktów
└── app_final_hiperlink_upload_podglad.py
```

---

## ℹ️ Dodatkowe informacje

- Jeśli chcesz korzystać z aplikacji w sieci lokalnej lub na serwerze – mogę przygotować instrukcję.
- Wersja dla Mac/Linux również dostępna na życzenie.

---

## ✉️ Pomoc

Masz pytania? Skontaktuj się lub zgłoś problem, a chętnie pomogę!

---

🛠️ Made with ❤️ by ChatGPT for Szymon Bihuniak
