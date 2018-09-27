# Demo Site For DrupalCorn 2018 Talk On Component Based Site Builds

## Setup

1) Install [Docksal]().
1) cd docroot
1) fin up
1) fin composer install

There are three sites "empty", "bricks", and "paragraphs" that are used for the demo and things are set up in a standard multisite installation. To initialize all three sites do the following.

1) fin restore empty init
1) fin restore bricks init
1) fin restore paragraphs init

After that you should be able to visit http://empty.drupalcorn2018.docksal, http://bricks.drupalcorn2018.docksal, and http://paragraphs.drupalcorn2018.docksal and see the sites as they were at the beginning of the presentation. This of course assumes that the directory containing this README file is named "drupalcorn2018".

*NOTE:* The settings.local.php file for all three sites containing the database connection info is checked into the repo. This makes it easy for folks to get things set up but would be a Really Bad Idea for any Drupal site that will ever be deployed on the internet.

## Presentation Slides

The slides for the presentation that the code in this repo was used for can be found at http://presentations.kedrovsky.com/drupalcorn2018.