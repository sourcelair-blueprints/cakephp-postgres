# CakePHP + PostgreSQL project template

Get started with a new CakePHP project, powered by PostgreSQL, on [SourceLair](https://www.sourcelair.com/home).

## Getting started

The easiest way to get started is by visiting http://lair.io/stacks/cakephp-postgres and starting a new SourceLair project with a single click.

This will do the following on your behalf:

1. create a new SourceLair project for your CakePHP + PostgreSQL app
2. clone the code from this Git repository
3. install your composer dependencies (`composer install`)
4. start an Apache server serving your project and expose it to your public URL

## Setting up the database

Your database server will be set up for you, you'll only need to create the database needed for your project. To do so:

1. type `psql -h postgres -U postgres`
2. enter your password, which is "mysecretpassword" by default
3. create a new database, by typing `create database my_app;`

That's it, you're ready to go!

### Database credentials

- host: `postgres`
- username: `postgres`
- password: `mysecretpassword`

### Is my data safe?

Of course it is, SourceLair databases are only available from within your project.

## Tips

- edit your files using SourceLair's fully-featured editor
- run commands (e.g. `bin/cake routes`) in SourceLair's Linux terminal
- view and test your CakePHP app using your public URL (click on the _eye_ icon in the sidebar)
- in case you need any help contact SourceLair using the _envelope_ icon in the sidebar or send an email to [support@sourcelair.com](mailto:support@sourcelair.com)

## License

The code provided in this template is licensed under the MIT License. For more information check out the [LICENSE](LICENSE) file.
