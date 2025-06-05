# AILab
This project is a microblogging platform inspired by X (formerly Twitter), designed to be scalable through a microservices architecture. The goal is to build a solid foundation to explore different artificial intelligence applications, investigating how AI can enhance user experience on the platform.
- Architecture: Microservices
- Technologies: Next.js, FastAPI, SQLAlchemy, PostgreSQL, Docker, Kubernetes
- Goal: Build a robust and scalable platform to experiment with AI applications

## Submodules

This repository uses Git submodules to keep the frontend and backend code in
separate repositories. When cloning the project make sure to initialize the
submodules so the `frontend` and `services` folders are populated:

```bash
git clone --recurse-submodules <repo-url>
```

If you already cloned the repository without the `--recurse-submodules` flag,
you can fetch them later with:

```bash
git submodule update --init --recursive
```
