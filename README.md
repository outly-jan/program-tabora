# Program tábora

Webová aplikace pro správu programu letního tábora.  

## Co aplikace umí

- **Program oddílů / družin** – každý oddíl si zadává vlastní program do časových bloků, možnost sloučení bloků, sdílení programu s dalšími oddíly
- **Táborová hra a celotáborové aktivity** – přehled her a aktivit s fyzickou náročností, příznakem „Ruší program" a výjimkami pro jednotlivé oddíly
- **Jídelníček** – správa jídel pro každý den tábora
- **Služby** – přehled a zadávání služeb a rádců dne
- **Výzvy** – terénní výzvy s oblastí (sever/západ/jih) a časovým rozsahem
- **Tee-pee** – rezervační systém pro sdílený stan
- **Pomůcky a materiál** – seznam potřeb ke každé aktivitě s možností označit jako připraveno
- **Celkový přehled** – souhrnná tabulka celého tábora po dnech
- **Historie změn** – automatický log všech úprav programu
- **Export do Excelu** – export celého programu

## Technologie

- **Backend:** Python 3.12, Flask, SQLAlchemy, SQLite
- **Frontend:** Bootstrap 5, Bootstrap Icons 1.13.1, Jinja2
- **Nasazení:** PythonAnywhere

## Spuštění lokálně

```bash
pip install flask flask-sqlalchemy openpyxl
python flask_app.py
```

Aplikace poběží na `http://localhost:5000`.

Pro výchozí přístupová hesla kontaktujte autora
