# Basis-Image
FROM node:18

# Arbeitsverzeichnis setzen
WORKDIR /app

# Dateien kopieren und Abhängigkeiten installieren
COPY package.json package-lock.json ./
RUN npm install

# App-Code kopieren
COPY . .

# Port festlegen
EXPOSE 3000

# Startkommando
CMD ["npm", "start"]
