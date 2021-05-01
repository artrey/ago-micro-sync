# REST to gRPC

1. Make crypto keys (only asymmetric keys are used):

```bash
cd services/auth/keys
docker-compose up
```

2. Copy the `public.key` to `services/backend/keys`:

```bash
cp services/auth/keys/public.key services/backend/keys
```

3. Run the whole system:

```bash
docker-compose up -d
```
