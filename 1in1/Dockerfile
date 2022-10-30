FROM python:3.8

ADD tf_threading.py .
ADD 5in1.py .
ADD mnist.npz .
RUN pip install tensorflow
RUN pip install click


# CMD ["python" , "./tf_threading.py" ]
