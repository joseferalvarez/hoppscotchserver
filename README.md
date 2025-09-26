# Steps to deploy hoppscotch

1. Change the env variables with your own urls.

2. Deploy the stack:

```bash
docker compose up -d
```

3. Make the migrations:

```bash
docker exec -it hoppscotch-hoppscotch-back-1 pnpm dlx prisma migrate deploy
```