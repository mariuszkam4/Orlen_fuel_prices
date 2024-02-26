# Orlen Fuel Prices Analysis and Eurodiesel Price Modeling

## Project Description
In this project, I analyze the interplay between Orlen's wholesale fuel prices in Poland, Brent crude oil prices, and the USD/PLN exchange rate, with the aim of understanding the impact of these global economic factors on Poland's fuel prices. A predictive model for Eurodiesel prices is developed, which could serve as a tool for economic forecasting and policy-making.

## Technologies and Tools
- **Programming Language**: Python
- **Libraries**: pandas, matplotlib, seaborn, sklearn, numpy
- **Environment**: Jupyter Notebook

## Project Workflow
### 1. Data Collection and Preparation
- **Data Retrieval**: Data on Brent oil prices, USD/PLN exchange rates, and Orlen wholesale fuel prices are collected from authentic sources in CSV format and via web scraping techniques.
- **Data Processing**: The collected data is cleaned for inconsistencies, formatted for analysis, and standardized to ensure data integrity. This includes converting date formats to pandas datetime and normalizing price formats for accurate comparisons.

### 2. Data Exploration
- **Statistical Analysis**: Employing pandas and numpy, I perform a detailed statistical analysis to establish baseline metrics such as mean, median, and standard deviation.
- **Data Visualization**: Using matplotlib and seaborn, I create a series of line and scatter plots to visualize price trends over time and explore the correlations between the various economic indicators.

### 3. Data Modeling
- **Linear Regression**: A linear regression model is first built as a baseline to predict Eurodiesel prices using Brent oil prices converted to PLN.
- **Random Forest Regression**: A more sophisticated Random Forest model is then developed to capture non-linear relationships and interactions between variables.

### 4. Model Validation
- **Cross-Validation**: To prevent overfitting, I perform k-fold cross-validation and calculate the mean squared error (MSE) to evaluate the Random Forest model's performance.
- **Evaluation Metrics**: The final model's accuracy is measured by computing the MSE and R² coefficient on the test set.

### 5. Conclusions
- **Results Analysis**: Insights into the patterns of fuel prices are derived, highlighting periods of significant divergence from the expected economic indicators.
- **Model Assessment**: The Random Forest model's predictions are assessed, showing its effectiveness in capturing complex relationships between variables and its potential use in forecasting.

## Installation and Usage
Ensure you have Python installed, and then run the following commands to install the required libraries:
pip install pandas matplotlib seaborn sklearn numpy

Execute the Jupyter notebook cell by cell to replicate the analysis.

## License
This project is released under the MIT License, allowing for open-source distribution and modification with proper attribution.

## PL
# Analiza cen paliw Orlen i modelowanie cen Eurodiesel
## Opis projektu
W tym projekcie analizuję interakcję między hurtowymi cenami paliw Orlen w Polsce, cenami ropy Brent i kursem wymiany USD/PLN, w celu zrozumienia wpływu tych globalnych czynników ekonomicznych na ceny paliw w Polsce. Opracowano model predykcyjny dla cen oleju napędowego Eurodiesel, który może służyć jako narzędzie do prognozowania gospodarczego i kształtowania polityki.

## Technologie i narzędzia
- **Język programowania**: Python
- **Biblioteki**: pandas, matplotlib, seaborn, sklearn, numpy
- **Środowisko**: Jupyter Notebook

## Przepływ pracy w projekcie
### 1. Gromadzenie i przygotowanie danych
- Pobieranie danych**: Dane dotyczące cen ropy Brent, kursów wymiany USD/PLN i hurtowych cen paliw Orlen są zbierane z autentycznych źródeł w formacie CSV i za pomocą technik skrobania stron internetowych.
- Przetwarzanie danych**: Zebrane dane są czyszczone pod kątem niespójności, formatowane do analizy i standaryzowane w celu zapewnienia integralności danych. Obejmuje to konwersję formatów dat na pandas datetime i normalizację formatów cen w celu dokładnego porównania.

### 2. Eksploracja danych
- **Analiza statystyczna**: Wykorzystując pandas i numpy, przeprowadzam szczegółową analizę statystyczną w celu ustalenia podstawowych wskaźników, takich jak średnia, mediana i odchylenie standardowe.
- **Wizualizacja danych**: Korzystając z matplotlib i seaborn, tworzę serię wykresów liniowych i rozproszonych w celu wizualizacji trendów cenowych w czasie i zbadania korelacji między różnymi wskaźnikami ekonomicznymi.

### 3. Modelowanie danych
- Regresja liniowa**: Model regresji liniowej jest najpierw budowany jako punkt odniesienia do przewidywania cen oleju napędowego Eurodiesel przy użyciu cen ropy Brent przeliczonych na PLN.
- **Random Forest Regression**: Bardziej zaawansowany model Random Forest jest następnie opracowywany w celu uchwycenia nieliniowych relacji i interakcji między zmiennymi.

### 4. Walidacja modelu
- **Walidacja krzyżowa**: Aby zapobiec nadmiernemu dopasowaniu, przeprowadzam k-krotną walidację krzyżową i obliczam średni błąd kwadratowy (MSE), aby ocenić wydajność modelu Random Forest.
- **Metryki oceny**: Dokładność ostatecznego modelu jest mierzona poprzez obliczenie MSE i współczynnika R² na zbiorze testowym.

### 5. Wnioski
- Analiza wyników**: Uzyskano wgląd we wzorce cen paliw, podkreślając okresy znacznych rozbieżności od oczekiwanych wskaźników ekonomicznych.
- **Ocena modelu**: Oceniono przewidywania modelu Random Forest, pokazując jego skuteczność w wychwytywaniu złożonych relacji między zmiennymi i jego potencjalne zastosowanie w prognozowaniu.

## Instalacja i użytkowanie
Upewnij się, że masz zainstalowany Python, a następnie uruchom następujące polecenia, aby zainstalować wymagane biblioteki:
pip install pandas matplotlib seaborn sklearn numpy

Uruchom notatnik Jupyter komórka po komórce, aby powtórzyć analizę.

## Licencja
Ten projekt jest wydany na licencji MIT, umożliwiającej dystrybucję i modyfikację open source z odpowiednim przypisaniem.
*** Przetłumaczono za pomocą www.DeepL.com/Translator (wersja darmowa) ***

