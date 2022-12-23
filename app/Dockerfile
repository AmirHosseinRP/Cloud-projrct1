FROM node
WORKDIR /app
COPY PingPong.js /app
EXPOSE 3001
RUN npm install express
RUN npm install cors
ENTRYPOINT ["node"]
CMD ["PingPong.js"]

