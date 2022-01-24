FROM python:3.8-slim

COPY docker/app_b/requirements.txt .
RUN python3.8 -m pip install --upgrade pip
RUN pip install -r requirements.txt

COPY apps/app_b.py .

ENTRYPOINT ["python3.8"]
CMD ["-m", "apps.app_b"]
