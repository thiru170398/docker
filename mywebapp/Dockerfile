FROM python:3.10
# Add application code to the container
ADD . /webapp/
# Upgrade pip and install dependencies
RUN pip install --upgrade pip
RUN pip install fastapi uvicorn
# Expose the port
EXPOSE 8001
# Command to run the application
CMD ["python", "webapp/main.py"]
