# Работа над фронтом
git checkout frontend
git add frontend/
git commit -m "feat: add map component"
git push origin frontend

# Работа над бэком
git checkout backend
git add backend/
git commit -m "feat: add layers endpoint"
git push origin backend

# Docker изменения
git checkout main
git add docker-compose.yml
git commit -m "chore: update docker-compose"
git push origin main