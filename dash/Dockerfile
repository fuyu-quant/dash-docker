FROM python:3.9.13-slim
USER root


# 環境系
ENV LANG="ja_JP.UTF-8" \
    LANGUAGE="ja_JP:ja" \
    LC_ALL="ja_JP.UTF-8"
ENV TZ JST-9



# Installing packages
COPY requirements.txt /root
WORKDIR /root
RUN pip install --no-cache-dir -r requirements.txt


ENTRYPOINT ["python", "src/app.py"]


