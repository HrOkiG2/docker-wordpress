## Technical Configuration
- PHP8.3
- MySQL8.0

## Method Of Proceeding
1. Create an environment variable file by copying .env.testing
2. Docker build && up
3. Access localhost:8000 to proceed with WordPress installation
4. Log in using values set in .env

## Supplement
1. .gitignore should be modified according to your environment.
2. This docker-compose is include Apache. If you want to use nginx, you cannot use this repository