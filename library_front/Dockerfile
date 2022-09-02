# Imagem de Origem
FROM node:17-alpine

WORKDIR /app

COPY package.json /app/package.json
 
RUN npm install

COPY . .

EXPOSE 3000
# Inicializa a aplicação
CMD ["npm", "start"]