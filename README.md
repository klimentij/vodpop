# Git Push Instructions

## Committing Changes
To commit your changes before pushing, use the following commands:

```sh
# Stage all changes
git add .

# Commit changes with a message
git commit -m "Your commit message here"
```

## Pushing Changes
To ensure a successful push, always use these commands:

```sh
# Dry run to check what will be pushed
git push origin main --dry-run

# Push with --no-thin to avoid issues
git push --no-thin origin main
```

Using `--no-thin` ensures that all objects are sent correctly, preventing issues that may arise from a partial push.

