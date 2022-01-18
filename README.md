# Rain in Australia


L'obiettivo del progetto è stato quello di costruire un modello predittivo per la previsione delle giornate di pioggia in Australia.
Il modello è stato allenato tramite i dati metereologici forniti dal dataset ed è in grado di predirre se il giorno dopo ci sarà pioggia o meno.
Come modello è stato utilizzato un regressore logistico (Logit) mediante la libreria python statsmodels.

Allo stato dell'arte il modello prevede con una precisione dell'85% se il giorno successivo ci sarà pioggia o meno (regressione binaria).

Inoltre sono state effettuate delle analisi di serie temporali per quanto riguarda alcune feature numeriche del dataset tramite la tecnica del Vector Autoregression (VAR).

E' stato utilizzato il dataset pubblico "Rain in Australia" disponibile su Kaggle (https://www.kaggle.com/jsphyg/weather-dataset-rattle-package).
