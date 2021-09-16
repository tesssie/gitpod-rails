# A Ruby on Rails with Postgres template on Gitpod

This is a [Ruby on Rails with Postgres](https://rubyonrails.org) template configured for ephemeral development environments on [Gitpod](https://www.gitpod.io/).

## Next Steps

Click the button below to start a new development environment:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/gitpod-io/template-ruby-on-rails-postgres)

## Get Started With Your Own Project

### A new project

Click the above "Open in Gitpod" button to start a new workspace. Once you're ready to push your first code changes, Gitpod will guide you to fork this project so you own it.

### An existing project

To get started with Ruby on Rails with Postgres on Gitpod, add a [`.gitpod.yml`](./.gitpod.yml) file which contains the configuration to improve the developer experience on Gitpod. To learn more, please see the [Getting Started](https://www.gitpod.io/docs/getting-started) documentation.

## Notes & caveats

* The template was generated using `rails new . -d postgres`
* [./gitpod.yml](./.gitpod.yml) launches the rails server bound to `0.0.0.0` so that the server is accessible in Gitpod. The default configuration binds to `localhost`.
* [config/environments/development.rb](./config/environments/development.rb) has been configured with `config.hosts.clear` to enable requests to the Gitpod subdomain. In this template the Ruby on Rails configuration interface has been set to private. If this setting is changed to public then anyone will be able to connect to the administration interface if they know the workspace name.
