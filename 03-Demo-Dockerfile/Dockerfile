FROM python:3.9.18-slim
WORKDIR /app
COPY    requirements.txt  .   
RUN    pip install  -r requirements.txt
COPY  . .
CMD   ["python" , "appy.py"]
EXPOSE 5000