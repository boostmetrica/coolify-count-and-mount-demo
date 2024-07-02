FROM alpine:3.14

# mount the files to copy
COPY ./files /app

COPY ./copy/copy.sh /usr/bin/copy.sh

CMD ["sh", "/usr/bin/copy.sh"]
