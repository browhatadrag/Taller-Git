# Taller-Git
My first repository

# 1. Clonar (si es fork, clona tu copia)
git clone https://github.com/TU_USUARIO/nombre-repo.git
cd nombre-repo

# 2. Crear rama
git checkout -b juan-perez

# 3. Crear archivo
echo "Hola, soy Juan Pérez." > juan-perez.txt

# 4. Subir cambios
git add .
git commit -m "Agrego archivo txt de Juan Pérez"
git push origin juan-perez

# 5. Hacer Pull Request → desde GitHub (web)