FROM python:3.13.11

RUN pip3 install news-please --upgrade

COPY docker.sh /
RUN chmod +x /docker.sh

CMD ["/docker.sh"]
