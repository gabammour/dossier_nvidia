library(quantmod)

# Définir la période
startDate <- as.Date("2017-01-01")
endDate <- as.Date("2022-12-31")

# Importer les données de l'action NVIDIA
getSymbols("NVDA", 
           from = startDate, 
           to = endDate, 
           src = "yahoo")

# Afficher les premières lignes des données
head(NVDA)

# Optionnel : Tracer le graphique des prix de clôture
chartSeries(NVDA, theme=chartTheme('white'))
