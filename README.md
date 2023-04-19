# wp-ddev-new

Sample Wordpress project with DDEV configured. The goal was to set up ddev for a new wordpress instance.

## How set up project

- create new project folder

  - `mkdir wp-site`

- go to project folder

  - `cd wp-site/`

- create a new DDEV project inside the newly-created folder

  - `ddev config --project-type=wordpress`

- run ddev

  - `ddev start`

- download WordPress

  - `ddev wp core download`

- launch in browser to finish installation

  - `ddev launch`

- OR use the following installation command
  - `ddev wp core install --url='$DDEV_PRIMARY_URL' --title='New-WordPress' --admin_user=admin --admin_email=admin@example.com --prompt=admin_password`
