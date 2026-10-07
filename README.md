docker run --rm --name postgres-dev \
  --env-file .env \
  -p 127.0.0.1:5432:5432 \
  -v postgres_data:/var/lib/postgresql \
  -d postgres:18