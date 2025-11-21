FROM python:3.12-slim

# install dev dependencies
WORKDIR /workspace

RUN apt-get update && apt-get install -y --no-install-recommends \
    build-essential \
    ...


# install python deps
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

CMD ["bash"]
