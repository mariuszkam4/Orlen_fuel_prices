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
#### Linear Regression
- Implemented a simple linear regression model to establish a baseline for predictive performance. This model predicts Eurodiesel prices based solely on the Brent oil prices converted to PLN.

#### Polynomial Regression
- To capture more complex relationships, a polynomial regression model was applied. This model includes higher-order terms of the input features to allow for a non-linear relationship between the predictors and the target variable.
- Learning and validation curves were plotted to assess the model's performance and to ensure the right balance between bias and variance, thus addressing any potential overfitting or underfitting.

#### Random Forest Regression
- A Random Forest model was then developed for its ability to handle non-linearities and interactions between features without explicit specification. It improves upon the simple regression models by using an ensemble of decision trees.
- The model's hyperparameters were tuned, and its performance was evaluated using cross-validation to ensure robust predictions. Feature importance was also derived to understand the influence of each predictor on the fuel prices.

#### ARIMAX Model
- Lastly, an ARIMAX (AutoRegressive Integrated Moving Average with eXogenous variables) model was employed to account for time-series characteristics such as trends, seasonality, and autocorrelation in the data.
- The ARIMAX model included external variables like Brent oil prices and the USD/PLN exchange rate to predict Eurodiesel prices, leveraging the temporal dynamics in conjunction with the economic factors.

### 4. Model Validation
- Cross-Validation: Extensive k-fold cross-validation was conducted for each model to assess its predictive accuracy and to mitigate the risk of overfitting.
- Evaluation Metrics: Models were rigorously evaluated using Mean Squared Error (MSE) and the R² coefficient to quantify prediction errors and to explain the variance in Eurodiesel prices, respectively.

### 5. Conclusions
- **Results Analysis**: The analysis provided a multifaceted view of fuel price dynamics, underscoring the complex interplay between global economic factors and local pricing.
- **Model Assessment**: The comparative effectiveness of different models was discussed, highlighting the strengths of ensemble and time-series approaches in capturing the nuances of the dataset.


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
#### Regresja liniowa
- Wdrożono prosty model regresji liniowej, aby ustalić punkt odniesienia dla wydajności predykcyjnej. Model ten przewiduje ceny oleju napędowego Eurodiesel wyłącznie na podstawie cen ropy Brent przeliczonych na PLN.

#### Regresja wielomianowa
- Aby uchwycić bardziej złożone zależności, zastosowano model regresji wielomianowej. Model ten obejmuje warunki wyższego rzędu cech wejściowych, aby umożliwić nieliniową zależność między predyktorami a zmienną docelową.
- Krzywe uczenia i walidacji zostały wykreślone w celu oceny wydajności modelu i zapewnienia właściwej równowagi między odchyleniem a wariancją, tym samym zajmując się potencjalnym nadmiernym lub niedostatecznym dopasowaniem.

#### Random Forest Regression
- Model Random Forest został następnie opracowany ze względu na jego zdolność do obsługi nieliniowości i interakcji między cechami bez wyraźnej specyfikacji. Ulepsza on proste modele regresji, wykorzystując zespół drzew decyzyjnych.
- Dostrojono hiperparametry modelu, a jego wydajność oceniono za pomocą walidacji krzyżowej, aby zapewnić solidne przewidywania. Określono również znaczenie cech, aby zrozumieć wpływ każdego predyktora na ceny paliw.

#### Model ARIMAX
- Na koniec zastosowano model ARIMAX (AutoRegressive Integrated Moving Average with eXogenous variables) w celu uwzględnienia cech szeregów czasowych, takich jak trendy, sezonowość i autokorelacja w danych.
- Model ARIMAX obejmował zmienne zewnętrzne, takie jak ceny ropy Brent i kurs wymiany USD/PLN, aby przewidzieć ceny oleju napędowego Eurodiesel, wykorzystując dynamikę czasową w połączeniu z czynnikami ekonomicznymi.

### 4. Walidacja modelu
- Walidacja krzyżowa: Dla każdego modelu przeprowadzono szeroko zakrojoną k-krotną walidację krzyżową, aby ocenić jego dokładność predykcyjną i zmniejszyć ryzyko nadmiernego dopasowania.
- Wskaźniki oceny: Modele zostały poddane rygorystycznej ocenie przy użyciu średniego błędu kwadratowego (MSE) i współczynnika R² w celu ilościowego określenia błędów predykcji i wyjaśnienia wariancji cen oleju napędowego Eurodiesel.

### 5. Wnioski
- Analiza wyników**: Analiza dostarczyła wieloaspektowego spojrzenia na dynamikę cen paliw, podkreślając złożoną interakcję między globalnymi czynnikami ekonomicznymi a lokalnymi cenami.
- **Ocena modelu**: Omówiono skuteczność porównawczą różnych modeli, podkreślając mocne strony podejścia zespołowego i szeregów czasowych w uchwyceniu niuansów zbioru danych.

## Instalacja i użytkowanie
Upewnij się, że masz zainstalowany Python, a następnie uruchom następujące polecenia, aby zainstalować wymagane biblioteki:
pip install pandas matplotlib seaborn sklearn numpy

Uruchom notatnik Jupyter komórka po komórce, aby powtórzyć analizę.

## Licencja
Ten projekt jest wydany na licencji MIT, umożliwiającej dystrybucję i modyfikację open source z odpowiednim przypisaniem.


