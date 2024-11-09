hidra
dags hub -> para almacenamiento de ficheros muy grnade, trazabilidad de lo smodelos, ver métricas versionado como se va entrenando
mlflow-> dnd se alamcena artefactos de modelos y métricas
dvc-> versionado de datos -> traza de datos ver con que datos se ha entrenado modelo
shap interpretabilidad de los modelos
docker
fast api-> habilitar api para consumir modelo
streamlit
pre-commit -> herramienta obliga a tener buenas prácticas antes de hacer push va a hacer check de buenas prácticas, corrige algunas cosas automáticamente

./.venv/Scripts/activate
pip install pre-commit
pre-commit install
git remote add origin 
git push origin master

dvc
dvc add data
dvc push -r origin -> subir a dvc a dagshub 

git hub actions poner variable de entorno
secreto de aws