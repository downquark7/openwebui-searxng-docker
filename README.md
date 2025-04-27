Start with installing docker

```shell
docker compose up -d
```

After the searxng/settings.yml is added, modify it by adding the json to the section shown below:

```yaml
search:
  ...
  formats:
    - html
    - json
```

```shell
docker compose down
docker compose up -d
```
