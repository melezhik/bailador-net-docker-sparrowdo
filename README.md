# SYNOPSIS

Run [http://bailador.net](http://bailador.net) in docker container.

# USAGE

    $ git clone https://github.com/melezhik/bailador-net-docker-sparrowdo.git

    $ cd bailador-net-docker-sparrowdo

    $ docker build  -t bailador-net .

    $ docker run -d -p 3001:3001 bailador-net

    $ firefox 127.0.0.1:3001


# Author

Alexey Melezhik

# See also

[alpine-perl6](https://github.com/JJ/alpine-perl6) - base docker image 
