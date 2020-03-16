FROM gingko5460/node
ADD . /app/
WORKDIR /app
EXPOSE 3000
CMD  /usr/local/bin/pm2  start  /app/bin/www -i 3 --no-daemon
