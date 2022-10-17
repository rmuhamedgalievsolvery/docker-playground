FROM python:3.6.0-alpine
RUN apk update && apk add --no-cache curl
ADD static/ /src
WORKDIR /src
EXPOSE  8080
ENTRYPOINT ["python3", "-m", "http.server", "8080"]