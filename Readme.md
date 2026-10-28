# Работа над фронтом
git checkout frontend
git add frontend/
git commit -m "frontend"
git push origin frontend

# Работа над бэком
git checkout backend
git add backend/
git commit -m "backend"
git push origin backend

# Docker изменения
git checkout main
git add docker-compose.yml
git commit -m "Docker"
git push origin main

# Стягивание конкретных изменений
# Из ветки main в frontend || backend
git checkout frontend
git restore --source=main -- frontend/.vscode/typescriptreact.json
git add .
git commit -m ""