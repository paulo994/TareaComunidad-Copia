***Comando para ejecutar cuando se descarga de git:

1.- docker-compose up --build
luego de esto saldra error code 1

2.- docker-compose run web bundle install
se actualiza gemfile.lock

3.- docker-compose up --build
dejar que salga error code 1 detener

4.- docker-compose down
para bajar el docker-compose

5.- yarn install --check-files
para checkear archivos de yarn

6.- docker-compose up
dara error de db, mientras esto corre en otra
terminal ejecutar comando docker-compose run web rake db:create

todo esta funcionando como corresponde


***posiblemente los comando tenga que ejecutar como superusuario