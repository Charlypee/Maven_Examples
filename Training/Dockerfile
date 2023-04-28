FROM node:14
LABEL maintainer="charlypee"
WORKDIR /app
COPY . .
RUN mpm install
EXPOSE 1004
CMD ["node","index.js"]