# Use the official MySQL image from Docker Hub
FROM mysql:latest

# Set environment variables (optional)
RUN npm i mysql2-promise

# Expose the MySQL port (3306) for external connections (optional)
EXPOSE 3306


# Set environment variables
ENV DB_HOST='localhost'
ENV DB_USER='root' 
ENV DB_PASSWORD=''
ENV DB_NAME='portalbeta'
ENV MQTT_HOST="app.starkenn.com"
ENV MQTT_PORT="1883"
ENV MQTT_USERNAME="starkenn"
ENV MQTT_PASSWORD="semicolon"
ENV JWT_SECRET="SomeSecretVal"
ENV PORT = 8080
ENV EMAIL_USERNAME_NOREPLY = "noreply@starkenn.com"
ENV EMAIL_USERNAME_NOREPLY_PASS = "iuxz gvlk xknc gosy" 
ENV TESTSERVER_STARKENN_URL = "https://starkenn.com/"
ENV WHATSAPP_ADMIN_CONTACT = "918505091963"
ENV ACCESS_TOKEN = "EAAOMzpzDMA0BOZBCSH4ZBwUYiuXqwGB7Yu3V8tVocE1IFdMgRzYnqmJ3FUN3BdR2RGVoUdVZBFnlfKBpoeVKvqZC4i0wZAPAHuTEJ9pF3hqG3IfZCyeh3BTKacdXq3gqxuxs4vUQLZCigEQS87u4V88IviaWbY0aDSac7BzmmKmGgV26EiTBVZCRCufFpZBmdhlNg7MyDaiZCjivMqcQvirrf4jugqY5XNNagjCi63ZCRdJ9IWJ"
ENV WHATSAPP_URL = "https://graph.facebook.com/v17.0/106310365906448/messages"

ENV TESTING_HOST = 'localhost'
ENV TESTING_USER = 'root'
ENV TESTING_PASSWORD = ''
ENV TESTING_DATABASE = 'portalbetatesting'

# (Optional) Add custom configurations if needed
COPY ../config