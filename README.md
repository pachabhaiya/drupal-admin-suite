# Drupal Recipe - Admin Suite

## Add repository

```
ddev composer config repo.admin_suite vcs https://github.com/pachabhaiya/drupal-admin-suite.git
```

## Require recipe

```
ddev composer require pachabhaiya/admin_suite:dev-master
```

## Apply recipe

```
ddev drush recipe ../recipes/admin_suite
```

## Known issues

- [Stop copying block configuration from active theme when enabling a new theme](https://www.drupal.org/project/drupal/issues/3105597)
