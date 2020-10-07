FROM python:2.7
LABEL mantainer="hakuna-tata<610578197@qq.com>"
RUN pip install flask
COPY ./hello.py /app/
WORKDIR /app
EXPOSE 5000
CMD ["python", "hello.py"]
