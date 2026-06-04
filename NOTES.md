# Notes on Odoo 19 Setup

## Environment
- macOS (Apple Silicon)
- Python 3.12.0
- PostgreSQL 15
- Odoo 19.0 (cloned from official repository)

## Run command
```bash
python odoo-bin -d odoo_dev --db_host=localhost --db_user=odoo \
    --db_password= --addons-path=addons --http-port=8069
```

## VS Code launch.json
Configured Python Debugger with debugpy to launch odoo-bin directly from IDE.

## Default credentials
- URL: http://localhost:8069
- Login: admin
- Password: admin
