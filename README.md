# Compose Image Version Update

## What is this?

A tool to update the version of an image in a Docker Compose file.

## How to use

```bash
> compose-image-version-update -f docker-compose.yml -i my-image -v 1.0.0
```

or

```bash
> compose-image-version-update test:1.0.0
```

The tool will search for a YAML file with a `compose` key in the current directory and update the image version to 1.0.0.

If the tool can't find the docker-compose.yml file, it will prompt you to choose a YAML file to search in the current directory.
