FROM node:12.10.0-alpine
MAINTAINER Jeff YU, jeff@jamma.cn
RUN yarn config set registry https://registry.npm.taobao.org
ENV NODE_ENV production
RUN mkdir -p /app
WORKDIR /app
CMD npm start