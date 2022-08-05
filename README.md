
## Pasos a seguir para levantar este proyecto con transbank 

 
versión de ruby:   ruby '2.5.3' 

versión de rails:  gem 'rails', '~> 6.1.6'



```shell
bundle install 
```
### instalar webpacker para que corra bien javascript
```shell
yarn add @rails/webpacker
```
## para cargar las migraciones de la base de datos
```shell 
rails db:migrate 
```
## para precargar datos automaticamente
```shell
rails db:seed
```
## para correr 
```shell
rails s
```
