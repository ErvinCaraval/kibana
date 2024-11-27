# Usar una imagen base de Node.js
FROM node:18

# Establecer el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiar el archivo package.json y package-lock.json al contenedor
COPY package.json .

# Copiar el resto de los archivos al contenedor
COPY kibana.js .


# Instalar las dependencias
RUN npm install

# Ejecutar el script de inicio del package.json (npm start)
CMD ["npm", "start"]


