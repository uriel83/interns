FROM node:14.15.0

RUN mkdir /project

WORKDIR /project

COPY ./package.json /project/package.json

RUN npm i 

COPY ./ /project/  

EXPOSE 5001

# ENTRYPOINT [ "tail" ]
# CMD ["-f","/dev/null"]

