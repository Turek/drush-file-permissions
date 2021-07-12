


## In your project

Configure the installer path for drush plugins in your main project's composer.json

```bash
{
  "extra": {
    "installer-paths": {
      "drush/contrib/{$name}": ["type:drupal-drush"]
    }
  }
}
```
