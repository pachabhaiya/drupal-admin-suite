# Drupal Recipe - Admin Experience

## Add repository

```
ddev composer config repo.admin_experience vcs https://github.com/pachabhaiya/drupal-admin-experience.git
```

## Require recipe

```
ddev composer require pachabhaiya/admin_experience:dev-master
```

## Apply recipe

```
ddev drush recipe ../recipes/admin_experience
```

## Known issues

- [Stop copying block configuration from active theme when enabling a new theme](https://www.drupal.org/project/drupal/issues/3105597)
