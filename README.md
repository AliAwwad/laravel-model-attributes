# Laravel Model Attributes package for Atom Editor

Laravel Model Attributes package for Atom targets a Laravel+MySQL projects to assist developers with autocomplete functionality to auto-complete a given Model by taking its name to guess the mysql related table.

Note: Right now it works only if you define you variables like: `$item = new User()`, the package will look for table `users` in your database and get back the columns.

**First Release, This is a beta**

This package is a provider for `autocomplete-plus` package (bundled with Atom)

<img src="images/laravel-model-attributes-screenshot-01.png" width="300" />



### Requirements:
- Atom `autocomplete-plus` package (bundled with Atom)
- Now is mandatory have PHP in the environment PATH

### Installation
- `apm install laravel-model-attributes`
- or install through Atom's UI

### Settings
- Enter Database name, user, password and host

### To-Do
- [ ] return Model custom methods
- [ ] find Model by `use App\Class` statement (to break free from pluralize model name to get table name)

### Maybe

### Thanks to:
- MySQL Nodejs library, it made this possible.
- Vinkla `autocomplete-tailwind`, great package, I went through its code and learned how to make a provider for `autocomplete-plus`.
- Azakur4 `autocomplete-php`, which I copied his README file layout.
