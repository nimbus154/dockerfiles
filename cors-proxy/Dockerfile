# Configure a container for installing npm modules, including compiled modules
FROM nimbus154/nodejs-builder:6
RUN mkdir /app && git clone https://github.com/Rob--W/cors-anywhere /app && cd /app && npm install
CMD ["node", "/app/server.js"]
