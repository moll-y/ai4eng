# Hotel Booking: [video](https://www.youtube.com/watch?v=6kQz3kwmcYI)

## Miembros del grupo

- Cristian Camilo Serna Betancur, CC 1018351871, Ingeniería de Sistemas
- Diego Alonso Herrera Ramírez, CC 70908268, Ingeniería de Sistemas
- Sharid Samantha Madrid Ospina, CC 1001652997, Ingeniería de Sistemas

## Datos
Los datos del proyecto vienen de La competición Kaggle Hotel Booking Dataset,
puedes acceder a través del siguiente enlace: [Hotel Booking Dataset](https://www.kaggle.com/datasets/saadharoon27/hotel-booking-dataset)

A continuación, se proporciona el código para cargar el conjunto de datos original utilizando pandas:

```py
import pandas as pd
data = pd.read_csv("https://raw.githubusercontent.com/Udeaproject/IA-system/main/hotel_booking.csv", delimiter=",")
print(data.columns)
```

Este código te permitirá cargar el conjunto de datos en un entorno como Colab y mostrar las columnas disponibles en el conjunto de datos.
