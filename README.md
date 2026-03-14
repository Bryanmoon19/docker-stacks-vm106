# Docker Stacks - VM 106

Docker Compose stack for VM 106 (192.168.7.219)

## Workflow

1. Edit `docker-compose.yml` on GitHub or locally
2. Push to `main` branch
3. GitHub Actions automatically deploys to VM 106

## Secrets Required

- `VM_SSH_KEY` — Private SSH key for bmoon19@192.168.7.219

## Testing

Make any change to `docker-compose.yml`, commit and push. Check the Actions tab on GitHub to see the deployment.
