# serverkit-rbenv
[Serverkit](https://github.com/r7kamura/serverkit) plug-in for [rbenv](https://github.com/sstephenson/rbenv).

## Resource
### rbenv_ruby
Install Ruby with rbenv.

#### Attributes
- version - Installed Ruby version (required) (e.g. `"2.2.0"`)
- rbenv_executable_path - Path to rbenv executable (e.g. `"/usr/local/bin/rbenv"`)
- global - Pass true to make it global (default: `false`)

#### Example
```yml
- id: install_ruby
  type: rbenv_ruby
  version: 2.2.0
  global: true
```