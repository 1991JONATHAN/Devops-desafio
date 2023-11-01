# Usa una imagen base de Node.js
FROM node:14

# Establece el directorio de trabajo
WORKDIR /app

# Copia los archivos de tu aplicación al contenedor
COPY . /app

# Instala las dependencias
RUN npm install

# Define un comando para iniciar la aplicación (por ejemplo, construir y ejecutar la aplicación)
CMD ["npm", "start"]
