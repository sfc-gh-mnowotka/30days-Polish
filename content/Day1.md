# Konfigurowanie lokalnego środowiska programistycznego

Zanim faktycznie zaczniemy tworzyć aplikacje Streamlit, najpierw będziemy musieli skonfigurować środowisko programistyczne.

Zacznijmy od zainstalowania i skonfigurowania środowiska Conda.

## **Instalacja condy**
- Zainstaluj `condę` wchodząc na stronę https://docs.conda.io/en/latest/miniconda.html i wyberając swój system operacyjny (Windows, Mac albo Linux). 
- Ściągnij i uruchom instalator aby zainstalować pakiet `conda`.

## **Stwórz nowe środowisko condy**
Kiedy masz już zainstalowaną condę, możemy stworzyć środowisko do zarządzania wszystkimi zależnościami bibliotek Pythona.

Aby stworzyć nowe środowisko korzystające z Pythona w wersji 3.9, wpisz w konsoli:
```bash
conda create -n stenv python=3.9
```

gdzie `create -n stenv` utworzy nowe środowisko o nazwie `stenv` a `python=3.9` skonfiguruje środowisko condy używajac Pythona w wersji 3.9.

## **Aktywuj nowo utworzone środowisko**

Aby skorzystać ze środowiska condy, które właśnie stworzyliśmy i które nazwaliśmy `stenv`, wprowadź następujące polecenie w linii poleceń:

```bash
conda activate stenv
```

## **Zainstaluj bibliotekę Streamlit**

Nadszedł czas aby wreszcie zainstalować samą bibliotekę `streamlit`:
```bash
pip install streamlit
```

## **Uruchaianie przykładowej aplikacji**
Aby uruchomić przykładową aplikację, wpisz:
```bash
streamlit hello
```
