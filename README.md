# Mercury Editor Demo Recipe

A Drupal recipe that sets up a fully working [Mercury Editor](https://www.drupal.org/project/mercury_editor) demo — content type, paragraph components, sample content, and Style Options — all in one command.

## Requirements

- Drupal 10.3 or 11
- Composer
- Drush

## Installation

**1. Require the recipe via Composer** (from your project root):

```bash
composer require atendesigngroup/mercury_editor_demo_recipe
```

**2. Apply the recipe** (from your Drupal docroot, e.g. `web/`):

```bash
drush recipe ../recipes/mercury_editor_demo_recipe
```

## Usage

After applying the recipe:

- Go to **Content** and open **"Drupal Like You've Never Seen It"** — a sample page pre-loaded with demo components.
- Click **Edit** to explore Mercury Editor with all paragraph types loaded.
- Or go to **Content → Add content → ME Test CT** to build a new page from scratch.

## What the recipe installs

- **ME Test CT** content type, pre-configured for Mercury Editor
- **8 paragraph types**: Button, Card, Divider, Heading, Image, Section, Slideshow, Text
- **Multi-column Section layouts**: 1, 2, 2-bricks, 3 (25/50/25), and 3 (33/34/33) columns
- **Style Options** on Button, Card, and Divider components
- **Sample page** with 88+ demo paragraphs
- All required modules (see `composer.json`)

## Maintainers

Maintained by [Aten Design Group](https://www.drupal.org/atendesigngroup).

- Project page: https://www.drupal.org/project/mercury_editor_demo_recipe
- Issue queue: https://www.drupal.org/project/issues/mercury_editor_demo_recipe
