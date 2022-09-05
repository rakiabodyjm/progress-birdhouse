This application is for demo purposes only

# Progressive Birdhouse

- [Frontend Next.js Repo](https://github.com/rakiabodyjm/progressive)
- [Backend NestJS Repo](https://github.com/rakiabodyjm/birdhouse)

**1**. Cloning with Submodules:

```bash
git clone --recurse-submodules https://github.com/rakiabodyjm/progressive-birdhouse
```

**2**. Running docker instances

```bash
docker compose up
```

_This pulls 2 images from Docker Hub, configured nginx and sql-server images._

> By default, nginx uses Port **80** and rewrites requests to frontend at URL `/` and backend requests at URL `/api`

---

> Login Credentials are autofilled upon Login
