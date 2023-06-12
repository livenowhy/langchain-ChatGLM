# build front-end
FROM registry.cn-beijing.aliyuncs.com/livenowhy/node:lts-alpine3.18 AS frontend

RUN npm install pnpm -g

WORKDIR /app

COPY . /app

#RUN pnpm run build



#COPY --from=frontend /app/dist /app/public

#EXPOSE 3002

#CMD ["pnpm", "run", "preview"]
