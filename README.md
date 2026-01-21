# Wallabag

A self-hosted application for managing wallabag.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/wallabag/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/wallabag" ~/.local/srv/docker/wallabag
cd ~/.local/srv/docker/wallabag
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install wallabag
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
