# Mi API FastAPI - Semana 2

## ¿Qué hace?

API mejorada con validación automática de datos y type hints.

## Nuevos Features (Semana 2)

- ✅ Type hints en todas las funciones
- ✅ Validación automática con Pydantic
- ✅ Endpoint POST para crear datos
- ✅ Parámetros de ruta (ejemplo: /products/{id})
- ✅ Búsqueda con parámetros query

## ¿Cómo ejecutar?

```bash
pip install fastapi pydantic uvicorn
uvicorn main:app --reload
```


**2. Subir a GitHub** (10 min):

```bash
# En tu terminal, en la carpeta de tu proyecto
git add .
git commit -m "Semana 2: API con Pydantic y Type Hints"
git push 

**Frases de lo importate que fue aprender en la semana**

-Aprender a usar Pydantic y type hints fortaleció la robustez y claridad del código, haciendo más confiable la validación de datos.

-Implementar endpoints con parámetros de ruta y query me permitió crear una API más dinámica y útil para distintos escenarios de búsqueda y gestión.

-Construir un CRUD básico con respuestas personalizadas me ayudó a comprender cómo estructurar una API real que sea fácil de usar y mantener.