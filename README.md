# SlimerJS

SlimerJS, CasperJS in a Docker container.

Fork of [cmfaith/slimerjs](https://hub.docker.com/r/cmfatih/slimerjs/).

# Usage
    docker run chetbox/slimerjs /usr/bin/slimerjs -v
    docker run chetbox/slimerjs /usr/bin/casperjs | head -n 1
    docker run -v `pwd`:/mnt/test chetbox/slimerjs /usr/bin/slimerjs /mnt/test/test.js
