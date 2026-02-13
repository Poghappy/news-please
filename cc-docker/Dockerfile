FROM python:3.14.3

RUN pip3 install news-please --upgrade

COPY docker.sh /
RUN chmod +x /docker.sh

CMD ["/docker.sh"]
