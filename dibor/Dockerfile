    #node env
    FROM node:18
    
    #workdir
    WORKDIR /app

    #copy the dependencies
    COPY package*.json ./

    #install the dependencies
    RUN npm install

    #Copy src code
    COPY . .

    CMD ["npm" , "start"]




