
```text
weboi2
├───app
│   ├───model                          # Modelos DB
│   ├───utilities                      # Dependencias composer, phpmailer.
│   └───view                           # Vistas / HTML
│       ├───back_end                   # Vistas privadas, login, etc.
│       │       └───includes
│       └───front_end                  # Vistas públicas y recursos a usar.
│           └───2025
│               ├───css
│               ├───img
│               └───js
├── index.php                        # Inicio de la web, include: inc.aplication_top.php y run.php
├── inc.aplication_top.php           # Configuración de sesion y base de datos.
├── run.php                          # Controlador frontal, define vista a mostrar por la url (param1,param2)