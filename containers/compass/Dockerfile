FROM ubuntu:14.04

RUN apt-get update && apt-get install -y \
    ruby-dev \
    make

RUN gem install breakpoint -v 2.0.6
RUN gem install compass -v 0.12.5
RUN gem install sass -v 3.2.19
RUN gem install zen-grids -v 1.4

ENTRYPOINT ["/bin/bash"]