FROM python:3.8-slim

COPY docker/app_a/requirements.txt .
RUN python3.8 -m pip install --upgrade pip
RUN pip install -r requirements.txt

COPY apps/app_a.py .

ENTRYPOINT ["python3.8"]
CMD ["-m", "apps.app_a"]
