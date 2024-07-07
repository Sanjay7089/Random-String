FROM python:3.8
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt

# Set the PORT environment variable
ENV PORT 5000

# Expose the port (optional but good practice)
EXPOSE 5000

CMD [ "python", "app.py" ]