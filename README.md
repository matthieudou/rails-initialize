
# Rails-initialize
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
- [simple_form](https://github.com/plataformatec/simple_form): Generating a custom `simple_form_for`
- `git`: Creating the initial commit.

## `rails-materialize` Template
Rails template based on [Materilal design](https://material.io/guidelines/), and more precisely on the [Materialize css](http://materializecss.com/) framework.

```shell
rails new APP_NAME -m https://raw.githubusercontent.com/matthieudou/rails-initialize/master/templates/rails-materialize.rb --database=postgresql
```
## `rails-bootstrap-material` Template
Rails template based on the bootstrap framework from twitter. It comes with a material design theme on it.

```shell
rails new APP_NAME -m https://raw.githubusercontent.com/matthieudou/rails-initialize/master/templates/rails-bootstrap-material.rb --database=postgresql
```
