# 🇵🇱 Wizualizacja Danych Geoprzestrzennych - Polska

Projekt w języku Python służący do analizy i wizualizacji danych statystycznych (m.in. stopy bezrobocia) na mapie administracyjnej Polski. Wykorzystuje biblioteki **GeoPandas** oraz **Folium** do tworzenia zarówno statycznych, jak i interaktywnych map. Projekt przedstawia przykładowe wykorzystania tych bibliotek.

## 🚀 Funkcjonalności

* **Wczytywanie danych przestrzennych:** Obsługa plików wektorowych (Shapefile `.shp`) z podziałem administracyjnym Polski (województwa).
* **Przetwarzanie danych:** Integracja danych geometrycznych z danymi statystycznymi (np. `Stopa bezrobocia w %`, `Bezrobotni w tys.`).
* **Wizualizacja statyczna:** Generowanie wykresów map przy użyciu `matplotlib` i `contextily`.
* **Mapy interaktywne:** Tworzenie map w `Folium` z możliwością przybliżania, najeżdżania na obszary (tooltipy) i legendą.
* **Eksport:** Możliwość zapisu gotowych wizualizacji do formatów graficznych lub HTML.

## 🛠️ Technologie i Biblioteki

Projekt został stworzony w środowisku Jupyter Notebook przy użyciu:

* **Python 3.x**
* **[GeoPandas](https://geopandas.org/)** – operacje na danych przestrzennych
* **[Pandas](https://pandas.pydata.org/)** – analiza i manipulacja danymi
* **[Folium](https://python-visualization.github.io/folium/)** – interaktywne mapy (Leaflet.js)
* **[Matplotlib](https://matplotlib.org/)** – wizualizacja danych
* **[Contextily](https://contextily.readthedocs.io/)** – podkłady mapowe (basemaps)
