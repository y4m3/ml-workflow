# ML-Workflow Template

A template for a machine learning environment.

- base docker image: `nvcr.io/nvidia/pytorch:21.02-py3`
- work GPUs
- MLFlow ready to use
    - mysql and minIO

sample

```bash
docker-compose --env-file ./settings/.env.sample up -d
```