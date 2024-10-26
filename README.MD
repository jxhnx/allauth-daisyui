# Django Allauth templates for DaisyUI

Django Allauth templates with basic DaisyUI styling. You can find a list of available allauth templates [here](https://docs.allauth.org/en/dev/common/templates.html).

## Installation

1. Copy the contents of the templates directory into your templates folder.
2. If not done already, register the templates in your settings.py, e.g., with:
    ```
    TEMPLATES = [
    {
        "DIRS": [
            str(APPS_DIR / "templates"),
        ],
        "APP_DIRS": True,
        ...
        },
    ]
    ```
3. Make sure to adjust the entry template `base.html` in `templates/allauth/layouts/entrance.html` and `templates/allauth/layouts/manage.html`