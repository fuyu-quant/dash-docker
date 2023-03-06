FROM python:3.9.13-buster
USER root


# 環境系
ENV LANG="ja_JP.UTF-8" \
    LANGUAGE="ja_JP:ja" \
    LC_ALL="ja_JP.UTF-8"
ENV TZ JST-9



# パッケージのインストール
COPY requirements.txt /root
WORKDIR /root
RUN pip install --no-cache-dir -r requirements.txt

# dashの不具合のため
#RUN pip uninstall werkzeug
#RUN pip install werkzeug==2.0.0


#EXPOSE 5050
CMD ["bash"]


Linux 64-bit: https://github.com/duckdb/duckdb/releases/download/v0.7.1/duckdb_cli-linux-amd64.zip

Linux 32-bit: https://github.com/duckdb/duckdb/releases/download/v0.7.1/duckdb_cli-linux-i386.zip

Linux Raspberry Pi: https://github.com/duckdb/duckdb/releases/download/v0.7.1/duckdb_cli-linux-rpi.zip


Win 64-bit: https://github.com/duckdb/duckdb/releases/download/v0.7.1/duckdb_cli-windows-amd64.zip

Win 32-bit: https://github.com/duckdb/duckdb/releases/download/v0.7.1/duckdb_cli-windows-i386.zip