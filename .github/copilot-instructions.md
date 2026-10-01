# Drupal 11 project (DDEV on Windows)
- Run everything through DDEV: `ddev drush ...`, `ddev composer ...`
- The site URL is https://drupal11-fresh.ddev.site:33001
- Custom code goes in web/modules/custom and web/themes/custom
- Never edit core or contrib; use hooks, plugins, services, dependency injection
- Follow Drupal coding standards
- Export config with `ddev drush cex -y`; clear cache with `ddev drush cr`
- Use current Drupal 11 APIs only (no deprecated code)
- The terminal is Windows PowerShell: avoid Linux-only commands like `rm -rf` or `cp -a`