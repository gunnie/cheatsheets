##Commands for the gloud tool

List all my accounts:

`gcloud auth list`

List all my configurations:

`gcloud config configurations list`

List details of current configuration:

`gcloud config list`

Create configuration:

`gcloud config configurations create <CONFIG_NAME>`

Activate configuration:

`gcloud config configurations activate <CONFIG_NAME>`

Set configuration project property:

`gcloud config set project <PROJECT_NAME>`

Prevent deployment from setting the default application version:

`gcloud config set app/promote_by_default false`

Deploy AppEngine App:

`gcloud app deploy -v <VERSION_NAME>`

Alternative way to deploy an AppEngine app:

`gcloud app deploy ~/my_app/app.yaml`

Deploying multiple AppEngine services:

`gcloud app deploy ~/my_app/app.yaml ~/my_app/another_service.yaml`
