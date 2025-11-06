# ==== CREAR Y CONFIGURAR REPOSITORIO ====
# Reemplaza TOKEN_GITHUB por tu token personal de acceso a GitHub
# (Puedes generarlo en https://github.com/settings/tokens)

# Variables del proyecto
USER_GITHUB="willian134"
REPO_NAME="mi-proyect"
GITHUB_TOKEN="TOKEN_GITHUB"

# Crear carpeta del proyecto
mkdir $REPO_NAME
cd $REPO_NAME

# ==== ARCHIVOS BASE ====

# README.md
cat << 'EOF' > README.md
# mi-proyect

Proyecto creado por **willian134**.

## Descripción
Este es un proyecto base en Python.

## Ejecución
```bash
python src/main.py
