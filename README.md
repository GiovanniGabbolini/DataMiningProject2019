# Description
In the context of the Data Mining class at Polimi, we were asked to forecast prediction for car speeds in traffic when affected by special events occourring in the streets, such as accidents and weather conditions changes. The performance were evaluated using MAE.

## Dataset
We were given a 1M+ interactions dataset recording speeds of the cars in serveral roads. We had at our disposal also other three side datasets containing informations about the sensor, the streets and the weather

## Our solution
We used Gradient Boosted trees with a chain of models to predict multiple speed steps over time. In particular, LightGBM and CatBoost were employed. Afterwards, we avaraged the predictions

## Results
We ranked first over eight other teams with a MAE of 8.5 Km/h in the private test set
