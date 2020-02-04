FROM python:3
WORKDIR /usr/src/app
copy requirments.txt ./
RUN pip install --no-cache-dir -r requirments.txt
COPY . .
CMD ["python", "app.py"]
