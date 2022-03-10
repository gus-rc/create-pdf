# README
## Crear PDF con ruby 

Este repositorio es para la creacion de PDF con las gemas de wicked_pdf y wkhtmltopdf-binary

Este repositorio se genero usando las versiones 
* Ruby 
    - ruby 2.7.2

* Rails 
    - rails 5.1.7    


Para intalar las gemas solo se debe ejecutar 
    `bundle install`

Para generar los registros de prueba 
    `rake db:migrate`
    `rake db:seed`

La aplicación se inicia con 
    `rails s`
y se puede consultar con 
`http://localhost:3000/products`

Para ver el PDF que se genera se debe consultar con: 

`http://localhost:3000/products.pdf`