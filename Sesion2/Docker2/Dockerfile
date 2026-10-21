# image Base
FROM python:3.9-slim

#Definir nuestro espacio de trabajo
WORKDIR /app

# Copiamos las librerias
COPY requirements.txt ./

# Instalamos las librerias
RUN pip install --no-cache-dir -r requirements.txt

# Copiar todo a la imagen
COPY . .

# Exposicion
EXPOSE 5000

CMD [ "python", "app.py"]