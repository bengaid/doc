FROM python:3.11

COPY app.py app.py
COPY label.png label.png
RUN pip install solara easyocr



ENTRYPOINT ["solara", "run", "app.py", "--host=0.0.0.0", "--port=80"]