# gympulse
# Inicialize o git (se ainda não estiver inicializado)
git init

# Adicione todos os arquivos
git add .

# Faça o primeiro commit
git commit -m "Initial commit - GymPulse application"

# Adicione o repositório remoto (substitua SEU-USUARIO e SEU-REPO)
git remote add origin https://github.com/SEU-USUARIO/SEU-REPO.git

# Envie o código para o GitHub
git branch -M main
git push -u origin main
