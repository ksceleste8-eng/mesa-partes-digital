# Prototipo de Mesa de Partes Digital

## Requisitos
- Python 3.9 o superior.
- No necesita instalar librerías externas.

## Ejecución
1. Abra una terminal en esta carpeta.
2. Ejecute: `python mesa_partes_digital.py`
3. Use el menú para registrar, buscar o listar expedientes.

Los registros se guardan automáticamente en `expedientes.json` en la misma carpeta.

## Control de versiones con Git y GitHub
Los comandos siguientes deben ejecutarse en la terminal, dentro de esta carpeta:

```bash
git init
git add mesa_partes_digital.py README.md
git commit -m "Paso 5: estructura inicial del prototipo"
git add mesa_partes_digital.py
git commit -m "Agregar validación y registro correlativo de expedientes"
git add mesa_partes_digital.py README.md
git commit -m "Implementar búsqueda, ordenamiento y persistencia"
```

Después cree un repositorio vacío en GitHub y siga las instrucciones que GitHub muestra para vincularlo. Habitualmente se usan:

```bash
git branch -M main
git remote add origin URL_DE_TU_REPOSITORIO
git push -u origin main
```

Reemplace `URL_DE_TU_REPOSITORIO` por la URL real que GitHub le proporcione. No se ha creado ni publicado un repositorio automáticamente; estos pasos permiten hacerlo desde su cuenta.
