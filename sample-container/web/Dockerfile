FROM amazoncorretto:21-al2023

RUN yum install -y \
    gcc-c++ \
    make \
    && curl -sL https://rpm.nodesource.com/setup_18.x | bash - \
    && yum install -y nodejs

WORKDIR /app
ENV TZ="Asia/Tokyo"