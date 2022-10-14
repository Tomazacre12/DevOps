FROM node:12-alpine
LABEL author="Hieu Vu"
WORKDIR /app/calculator
COPY ./package.json /app/calculator
COPY ./package-lock.json /app/calculator
RUN ls -al
RUN npm install
COPY . /app/calculator
EXPOSE 3000
CMD [*npm*, *start*]

