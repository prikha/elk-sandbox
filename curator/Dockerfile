FROM bobrik/curator:latest

ADD config/actionfile.yml /usr/share/curator/actionfile.yml
ADD config/curator.yml /usr/share/curator/curator.yml

ENTRYPOINT ["/usr/bin/curator"]
#CMD "--config /usr/share/curator/curator.yml /usr/share/curator/actionfile.yml"
