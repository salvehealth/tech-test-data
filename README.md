# Tech test data
 
The data to be served is contained in 3 separate files:
- `clinics.csv` - A list of clinics
- `patients-1.csv` - a list of patients belonging to clinic with ID 1
- `patients-2.csv` - a list of patients belonging to clinic with ID 2

The data models for these CSV files are as follows:

Clinic:
- `id: integer`
- `name: string`

Patient:
- `id: integer`
- `clinic_id: integer`
- `first_name: string`
- `last_name: string`
- `date_of_birth: string`


Given the relatively small size of the data sets, it is acceptable to process a full table of data in memory.

## Sample Data

`clinics.csv`
```
id,name
1,Salve Fertility
2,London IVF
```

`patients-1.csv`
```
id,clinic_id,first_name,last_name,date_of_birth
1,1,Harriott,Wansbury,1961-10-16
2,1,Glennis,Eustis,1985-04-08
3,1,Christie,Chasmer,1966-12-21
4,1,Clarice,Brookfield,1963-03-07
```

`patients-2.csv`
```
id,clinic_id,first_name,last_name,date_of_birth
1,2,Emlynn,Tompkin,1964-10-02
2,2,Kenyon,Domleo,1960-05-24
3,2,Denis,Christopherson,1983-11-23
```
