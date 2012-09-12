Django - APPFOG
===============

Instalação
-----------

    instale: http://ruby-lang.org/  &  http://rubygems.org/

Usando
------

    $ gem install af
    $ af login
    Email: seu-email-no-appfog@treta.com
    Password: *********
    Successfully logged into [https://api.appfog.com]

    $ git clone git://github.com/gladson/appfog_django.git
    $ cd appfog_django
    $ af push meu-appfog --url meu-site-app-fog.aws.af.cm

    Would you like to deploy from the current directory? [Yn]: y
    Detected a Python Django Application, is this correct? [Yn]: y
    1: AWS US East - Virginia
    2: AWS EU West - Ireland
    3: AWS Asia SE - Singapore
    4: Rackspace AZ 1 - Dallas
    5: HP AZ 2 - Las Vegas
    Select Infrastructure: 1
    Application Deployed URL [django.rs.af.cm]: meu-site-app-fog.aws.af.cm
    Memory reservation (128M, 256M, 512M, 1G, 2G) [128M]:
    How many instances? [1]: 1
    Create services to bind to 'django'? [yN]: y
    1: mongodb
    2: mysql
    3: postgresql
    What kind of service?: 2
    Specify the name of the service [mysql-4231c]: django_bd
    Create another? [yN]: N
    Would you like to save this configuration? [yN]: N
    Creating Application: OK
    Creating Service [django_bd]: OK
    Binding Service [django_bd]: OK
    Uploading Application:
        Checking for available resources: OK
        Processing resources: OK
        Packing application: OK
        Uploading (8K): OK
    Push Status: OK

    Staging Application 'django': OK

    Starting Application 'django': OK

# Pronto Funcionando... so isso

Detalhe
-------

1. Ja cria o admin automatico.
    Login: gladson
    senha: gladson

2. Impressionante como e fácil.