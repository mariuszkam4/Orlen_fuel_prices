# Orlen Fuel Prices Analysis and Eurodiesel Price Modeling
## Project Description
This project focuses on analyzing and modeling the relationship between Orlen's wholesale fuel prices in Poland, Brent crude oil prices, and the USD/PLN exchange rate. The objective is to understand the impact of global economic factors on fuel prices in Poland and develop a predictive model for Eurodiesel prices.

## Technologies and Tools
Programming Language: Python
Libraries: pandas, matplotlib, seaborn, sklearn, numpy
Environment: Jupyter Notebook

## Project Workflow
### 1. Data Collection and Preparation
Data Retrieval: Data on Brent oil prices, USD/PLN exchange rates, and Orlen wholesale fuel prices are collected from various sources in CSV format and via web scraping.
Data Processing: The data are cleaned, formatted, and standardized. Date and price formats are converted, and incomplete data are removed.
### 2. Data Exploration
Statistical Analysis: A statistical analysis of the data is conducted, including the calculation of means, medians, and standard deviations.
Data Visualization: Line and scatter plots are created to show price trends and correlations between different variables.
### 3. Data Modeling
Linear Regression: A linear regression model is built to predict Eurodiesel prices based on Brent oil prices converted to PLN.
Polynomial Regression: A polynomial regression analysis is conducted to improve the accuracy of predictions.
### 4. Model Validation
Learning and Validation Curves: Learning and validation curves are generated to assess the effectiveness of the model and identify overfitting or underfitting.
Evaluation Metrics: The model is evaluated using MSE and the R^2 coefficient.
### 5. Conclusions
Results Analysis: The project provides insights into fuel price patterns and their dependence on global economic indicators.
Model Assessment: The effectiveness and limitations of the predictive models are discussed.

## Installation and Usage

pip install pandas matplotlib seaborn sklearn numpy
Run the Jupyter notebook and proceed through the various stages of the project.

## License
The project is made available under the MIT License.

PL
# Analiza cen paliw Orlen i modelowanie cen Eurodiesel
## Opis projektu
Projekt koncentruje się na analizie i modelowaniu zależności między cenami hurtowymi paliw Orlen a cenami ropy Brent oraz kursem wymiany USD/PLN. Celem jest zrozumienie wpływu globalnych czynników ekonomicznych na ceny paliw w Polsce oraz rozwinięcie modelu predykcyjnego dla cen Eurodiesel.

## Technologie i narzędzia
Język programowania: Python
Biblioteki: pandas, matplotlib, seaborn, sklearn, numpy
Środowisko: Jupyter Notebook

## Proces realizacji projektu
### 1. Pobieranie i przygotowanie danych
Pobieranie danych: Dane o cenach ropy Brent, kursie USD/PLN i cenach hurtowych paliw Orlen są pobierane z różnych źródeł w formacie CSV oraz przez scraping stron internetowych.
Przetwarzanie danych: Dane są czyszczone, formatowane i standaryzowane. Następuje konwersja formatów dat i cen oraz usunięcie danych niekompletnych.
### 2. Eksploracja danych
Analiza statystyczna: Przeprowadzona jest analiza statystyczna danych, w tym obliczenie średnich, mediany i odchylenia standardowego.
Wizualizacja danych: Tworzone są wykresy liniowe i punktowe przedstawiające trendy cenowe oraz korelacje między różnymi zmiennymi.
### 3. Modelowanie danych
Regresja liniowa: Budowany jest model regresji liniowej przewidujący ceny Eurodiesel na podstawie cen ropy Brent przeliczonych na PLN.
Regresja wielomianowa: Przeprowadzona jest analiza za pomocą modelu regresji wielomianowej w celu zwiększenia dokładności predykcji.
### 4. Walidacja modelu
Krzywe uczenia i walidacji: Generowane są krzywe uczenia i walidacji w celu oceny efektywności modelu i identyfikacji overfittingu lub underfittingu.
Metryki oceny: Model jest oceniany przy użyciu MSE i współczynnika determinacji R^2.
### 5. Wnioski
Analiza wyników: Projekt dostarcza wniosków na temat wzorców cen paliw i ich zależności od globalnych wskaźników ekonomicznych.
Ocena modelu: Dyskutuje się skuteczność modeli predykcyjnych i ich ograniczenia.

## Instalacja i uruchomienie

pip install pandas matplotlib seaborn sklearn numpy
Uruchomienie notatnika Jupyter i przejście przez poszczególne etapy projektu.

## Licencja
Projekt jest udostępniony na licencji MIT.