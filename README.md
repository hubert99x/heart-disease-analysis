# English version above
# Polish version below
---

# 🫀 Analysis of Cardiovascular Disease Risk Factors

<br>

## 📊 Project Description

Course project for the Big Data class. The goal of the project was to perform a data analysis aimed at identifying risk factors for heart disease in the context of demographic characteristics and health habits.

Variables used in the analysis include: whether a person has been diagnosed with heart disease, BMI, smoking status, gender, and age category.

---

## 📁 Repository Contents

- `databricks_version/` – Version of the project intended to run exclusively on the Databricks platform  
  - `heart_analysis_databricks.ipynb`
- `local_version/` – Version of the project designed to run locally (Jupyter Notebook)  
  - `heart_analysis_local_version.ipynb`
- `.gitignore` – List of files and folders ignored by Git
- `README.md` – Project documentation and description

---

## 📝 Data and Dataset Description
The dataset used in this project was obtained from Kaggle:  
https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

The data published on Kaggle originates from the U.S. Behavioral Risk Factor Surveillance System (BRFSS), which is the largest global telephone-based health survey program.
The dataset was collected and published by the Centers for Disease Control and Prevention (CDC) as part of the annual health monitoring of residents in the United States.
The analyzed dataset contains data from the year **2020**.

---

## 🚀 Running the Project – Local Version (Jupyter Notebook)

#### ✅ Prerequisites

Python **3.10+** (with `pip`)

---

### 📦 Installation:

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/hubert99x/heart-disease-analysis
cd heart-disease-analysis/local_version
```

### 2️⃣ Create a virtual environment:

#### Linux/macOS:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

#### Windows (PowerShell or CMD):
```powershell
.venv\Scripts\activate
```

#### Windows (Git Bash):
```bash
python3 -m venv .venv
source .venv/Scripts/activate
```

### 3️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

### 4️⃣ Start Jupyter Notebook:
```bash
jupyter notebook
```

Then open the file: `heart_analysis_local_version.ipynb` located in `local_version`. Jupyter Notebook will open in your web browser.

---

<br>

# 🚀 Running the Project – Databricks Version

mport the file: `heart_analysis_databricks.ipynb.ipynb` from `databricks_version` directory.

On Databricks there is no need to create a virtual environment `venv` or install dependencies from `requirements.txt`, because most libraries (such as pandas, matplotlib, pyspark) are already preinstalled in the Databricks Runtime environment.

---
# 🫀 Analiza czynników ryzyka chorób sercowo-naczyniowych

<br>

## 📊 Opis projektu

Projekt zaliczeniowy na studiach z przedmiotu **Big Data**. Celem pracy było przeprowadzenie analizy danych mającej na celu zbadanie czynników ryzyka chorób serca w kontekście demografii i nawyków zdrowotnych. 

Wartości użyte w analizie: Czy u badanej osoby zdiagnozowano chorobę serca, BMI, Czy badana osoba jest osobą palącą, płeć i kategoria wiekowa.

---

## 📁 Zawartość repozytorium

- `databricks_version/` – Wersja projektu do uruchomienia wyłącznie na platformie Databricks  
  - `heart_analysis_databricks.ipynb`
- `local_version/` – Wersja projektu do uruchomienia lokalnie (Jupyter Notebook)  
  - `heart_analysis_local_version.ipynb`
- `.gitignore` – Lista plików i folderów ignorowanych przez Git
- `README.md` – Dokumentacja i opis projektu

---

## 📝 Dane i opis danych
Dane użyte w projekcie zostały pobrane z Kaggle: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

Dane udostępnione przez autora w Kaggle pochodzą z amerykańskiego systemu Behavioral Risk Factor Surveillance System (BRFSS), który jest największym globalnym programem ankiet telefonicznych badających stan zdrowia populacji.
Zostały one zebrane i udostępnione przez Centers for Disease Control and Prevention (CDC) jako część corocznego monitorowania zdrowia mieszkańców Stanów Zjednoczonych. Analizowany zbiór danych obejmuje rok 2020.

---

<br>

# 🚀 Uruchomienie projektu - Wersja lokalna (Jupyter Notebook)

#### ✅ Wymagania wstępne:
Python 3.10+ (z `pip`)

---

### 📦 Instalacja:

### 1️⃣ Sklonuj repozytorium:
```bash
   git clone https://github.com/hubert99x/heart-disease-analysis
   cd heart-disease-analysis/local_version
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

### 3️⃣ Zainstaluj zależności:
```bash
pip install -r requirements.txt
```

### 4️⃣ Uruchom Jupyter Notebook:
```bash
jupyter notebook
```

Następnie otwórz plik `heart_analysis_local_version.ipynb` w katalogu `local_version`. Jupyter Notebook otworzy się w przeglądarce.

---

<br>

# 🚀 Uruchomienie projektu - Wersja na platformie Databricks

Zaimportuj plik `heart_analysis_databricks.ipynb.ipynb` z katalogu `databricks_version`.

W Databricks nie ma potrzeby tworzenia wirtualnego środowiska `venv` ani instalowania zależności `requirements.txt`, ponieważ większość bibliotek (np. pandas, matplotlib, pyspark) jest już preinstalowana w środowisku Databricks Runtime.



