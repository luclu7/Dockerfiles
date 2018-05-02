FROM bash:latest

ADD https://raw.githubusercontent.com/dylanaraps/neofetch/master/neofetch /

RUN mkdir /root/.config/neofetch -p && mkdir //config/

ADD https://raw.githubusercontent.com/dylanaraps/neofetch/master/config/config.conf /root/.config/neofetch/
ADD https://raw.githubusercontent.com/dylanaraps/neofetch/master/config/config.conf //config/

ENTRYPOINT ["/usr/local/bin/bash"]

CMD ["/neofetch"]
