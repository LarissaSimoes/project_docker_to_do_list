FROM node:16

WORKDIR /app/back-end

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD ["start"]
