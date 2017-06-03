> The templates are currently under construction... ![](https://img.shields.io/teamcity/http/teamcity.jetbrains.com/s/bt345.svg)

# Rails Templates
Generating templates for rails apps with some default configs.
> Based on [LeWagon](https://github.com/lewagon/rails-templates) and [rails-templates](http://guides.rubyonrails.org/rails_application_templates.html)

For everything that follows, you need to have Rails installed. So if you don't have rails, you can run the next command.
```shell
gem install rails
```
All these templates are already implemented and configured with the following:

- [Figaro](https://github.com/laserlemon/figaro): preventing your `config/application.yml` from being uploaded on github.
- `app/assets`: Removing the auto-generated assets and replacing it with scss files.
- `application.html.erb`: Removing the auto-generated layout and replacing it with a custom one.
- `Readme.md`: Creating a basic readme.
- tests: Creating a test folder
- `git`: Creating the initial commit.

## `rails-materialize` Template
Rails template based on [Materilal design](https://material.io/guidelines/), and more precisely on the [Materialize css](http://materializecss.com/).

```shell
rails new APP_NAME -m https://github.com/matthieudou/rails-initialize/blob/master/templates/rails-materialize.rb --database=postgresql
```

## `rails-materialize-users` Template
todo

## `rails-bootstrap` Template
> Directly inspired from *LeWagon*.

todo

## `rails-bootstrap-users` Template
> Also inspired from *LeWagon*.

todo
