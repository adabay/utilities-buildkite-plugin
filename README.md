# Buildkite Utilities Plugin

This plugin exposes various utility scripts as reusable scripts to other commands of the same pipeline step where the plugin is included.

## Scripts
- `composer-install` - Runs the `composer install` command with production settings.

- `npm-install` - Runs the `npm ci` command with production settings.

- `clean-directory` - Recursively force-deletes all files in the directory, that is passed as the first argument to this script.