# Visualització de dades - Pràctica
## Part 2
## Joan Gómez i Tomé


```python
# Imports
import pandas as pd
```


```python
df = pd.read_csv('./accidents.csv', low_memory=False)
```


```python
print(df)
```

                    case_id  district_id district_name neighborhood_id  \
    0           2015S005807         -1.0    Desconegut            -1.0   
    1           2015S007685         10.0    Sant Martí            64.0   
    2           2015S001364         10.0    Sant Martí            64.0   
    3           2015S004325         10.0    Sant Martí            64.0   
    4           2015S005540         10.0    Sant Martí            64.0   
    ...                 ...          ...           ...             ...   
    110650  2019S010046              4.0     Les Corts              21   
    110651  2019S010047             10.0    Sant Martí              64   
    110652  2019S010048              2.0      Eixample               5   
    110653  2019S010049              4.0     Les Corts              19   
    110654  2019S010050              2.0      Eixample               6   
    
                     neighborhood_name  street_code  \
    0                       Desconegut         -1.0   
    1       el Camp de l'Arpa del Clot     134801.0   
    2       el Camp de l'Arpa del Clot     161407.0   
    3       el Camp de l'Arpa del Clot     226400.0   
    4       el Camp de l'Arpa del Clot      95506.0   
    ...                            ...          ...   
    110650                   Pedralbes     101700.0   
    110651  el Camp de l'Arpa del Clot     297001.0   
    110652               el Fort Pienc      28305.0   
    110653                   les Corts     167800.0   
    110654          la Sagrada Família     178308.0   
    
                                                  street_name postal_code  \
    0                                              Desconegut  Desconegut   
    1                                                  Freser   0208 0208   
    2                                               Indústria   0336 0336   
    3                                     Las Navas de Tolosa   0343 0343   
    4                                                   Conca   0032 0034   
    ...                                                   ...         ...   
    110650  Doctor Ferran / Manila                        ...   0025 0025   
    110651  Sant Antoni Maria Claret                      ...   0346 0348   
    110652  Ausiàs Marc / Nàpols                          ...   0080 0080   
    110653  Joaquim Molins                                ...   0009 0009   
    110654  Lepant                                        ...   0255 0255   
    
           weekday_name weekday  ...                  cause_incident  n_deaths  \
    0           Dimarts      Dm  ...        No és causa del  vianant       0.0   
    1           Dimarts      Dm  ...  Desobeir el senyal del semàfor       0.0   
    2          Dissabte      Ds  ...        No és causa del  vianant       0.0   
    3         Divendres      Dv  ...        No és causa del  vianant       0.0   
    4         Divendres      Dv  ...        No és causa del  vianant       0.0   
    ...             ...     ...  ...                             ...       ...   
    110650      Dimarts      Dm  ...        No és causa del  vianant       0.0   
    110651      Dimarts      Dm  ...        No és causa del  vianant       0.0   
    110652      Dimarts      Dm  ...        No és causa del  vianant       0.0   
    110653      Dimarts      Dm  ...        No és causa del  vianant       0.0   
    110654     Dimecres      Dc  ...        No és causa del  vianant       0.0   
    
            n_wounded_mild n_wounded_severe  n_victims  n_vehicles  \
    0                  2.0              0.0        2.0         2.0   
    1                  1.0              0.0        1.0         1.0   
    2                  1.0              0.0        1.0         1.0   
    3                  1.0              0.0        1.0         2.0   
    4                  2.0              0.0        2.0         1.0   
    ...                ...              ...        ...         ...   
    110650             1.0              0.0        1.0         1.0   
    110651             1.0              0.0        1.0         2.0   
    110652             1.0              0.0        1.0         2.0   
    110653             1.0              0.0        1.0         2.0   
    110654             0.0              1.0        1.0         2.0   
    
           utm_coordinate_y utm_coordinate_x  longitude   latitude  
    0                    -1               -1        NaN        NaN  
    1            4585420,58        431779,16        NaN        NaN  
    2            4585555,86        431913,65        NaN        NaN  
    3            4585565,44        431946,45        NaN        NaN  
    4            4585260,16        431530,84        NaN        NaN  
    ...                 ...              ...        ...        ...  
    110650       4582580,73        426884,52   2.124247  41.389610  
    110651       4585401,31        431576,15   2.180038  41.415427  
    110652       4583086,37        431561,78   2.180128  41.394576  
    110653       4582172,65        427314,36   2.129436  41.385974  
    110654       4584121,58        431324,88   2.177177  41.403880  
    
    [110655 rows x 27 columns]



```python

```
