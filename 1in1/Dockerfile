FROM python:3.8

ADD tf_threading.py .

RUN pip install tensorflow
RUN pip install numpy 

RUN pip install pandas

CMD ["python" , "./tf_threading.py" ]
