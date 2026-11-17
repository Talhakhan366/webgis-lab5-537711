# Web GIS Lab 5 - A spatial API with GeoDjango

Muhammad Talha Abdullah Khan (537711) - MS RS & GIS, IGIS, NUST

Django REST Framework + PostGIS API for districts (bbox / province filters) and
facilities (add from the map, validated in PostGIS, 25 km search).

## Run
```
python -m venv venv
venv\Scripts\Activate.ps1
pip install -r requirements.txt
$env:WEBGIS_DB_PASSWORD = "..."
python manage.py migrate
python manage.py runserver
```
Map: http://127.0.0.1:8000/  -  API: http://127.0.0.1:8000/api/

Report: [report.md](report.md)