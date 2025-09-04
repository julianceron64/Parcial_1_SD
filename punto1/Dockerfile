FROM alpine:3.20

WORKDIR /app

COPY mensaje.txt .

RUN apk add curl
COPY . .

CMD ["cat", "mensaje.txt"]
