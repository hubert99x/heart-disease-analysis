## ⚠️ Projekt można uruchomić na dwa sposoby ⬇️

<br>

## 📊 Opis projektu

Projekt zaliczeniowy na studiach z przedmiotu **Big Data**. Celem pracy było przeprowadzenie analizy danych mającej na celu zbadanie czynników ryzyka chorób serca w kontekście demografii i nawyków zdrowotnych. 

Wartości użyte w analizie: Czy u badanej osoby zdiagnozowano chorobę serca, BMI, Czy badana osoba jest osobą palącą, płeć i kategoria wiekowa.

---

## 📁 Zawartość repozytorium

- `databricks_version/` – Wersja projektu do uruchomienia wyłącznie na platformie Databricks  
  - `heart_analysis_databricks.ipynb`
- `local_version/` – Wersja projektu do uruchomienia lokalnie (VS Code, Jupyter Notebook)  
  - `heart_analysis_local_version.ipynb`
- `.gitignore` – Lista plików i folderów ignorowanych przez Git
- `README.md` – Dokumentacja i opis projektu

---

## 📝 Dane i opis danych
Dane użyte w projekcie zostały pobrane z Kaggle: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

Dane udostępnione przez autora w Kaggle pochodzą z amerykańskiego systemu Behavioral Risk Factor Surveillance System (BRFSS), który jest największym globalnym programem ankiet telefonicznych badających stan zdrowia populacji.
Zostały one zebrane i udostępnione przez Centers for Disease Control and Prevention (CDC) jako część corocznego monitorowania zdrowia mieszkańców Stanów Zjednoczonych. Analizowany zbiór danych obejmuje rok 2020.

---

## 🚀 Uruchomienie projektu - Wersja lokalna (Jupyter Notebook / VS Code)

#### ✅ Wymagania wstępne:
- Python 3.10+
- `pip`
- Środowisko wirtualne

### 📦 Instalacja:

### 1️⃣ Sklonuj repozytorium:
```bash
   git clone https://github.com/hubert99x/heart-disease-analysis
   cd heart-disease-analysis-project/local_version
```

### 2️⃣ Utwórz środowisko wirtualne:

#### Linux/macOS:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

#### Windows (PowerShell lub CMD):
```powershell
.venv\Scripts\activate
```

#### Windows (Git Bash):
```bash
python3 -m venv .venv
source .venv/Scripts/activate
```
---

### 3️⃣ Zainstaluj zależności:
```bash
pip install -r requirements.txt
```
---

### 4️⃣ Uruchom Jupyter Notebook:
```bash
jupyter notebook
```

Następnie otwórz plik `heart_analysis_local_version.ipynb` w katalogu `local_version`.

---

## 🚀 Uruchomienie projektu - Wersja na platformie Databricks

Zaimportuj plik `heart_analysis_databricks.ipynb.ipynb` z katalogu `databricks_version`.

W Databricks nie ma potrzeby tworzenia wirtualnego środowiska `venv` ani instalowania zależności `requirements.txt`, ponieważ większość bibliotek (np. pandas, matplotlib, pyspark) jest już preinstalowana w środowisku Databricks Runtime.







