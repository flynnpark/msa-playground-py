FROM base as base

WORKDIR /app

COPY pyproject.toml poetry.lock ./
RUN poetry install --no-root

# 소스 코드 복사
COPY . .
