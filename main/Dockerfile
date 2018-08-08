FROM resin/raspberrypi3-alpine

ENV INITSYSTEM=on
ENV UDEV=off

RUN cat /run/secrets/my-recipe

CMD ["ls", "-a"]