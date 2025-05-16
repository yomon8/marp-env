FROM mcr.microsoft.com/devcontainers/javascript-node:22-bookworm

# Install Chrome for Marp PDF/PPTX export
RUN apt-get update && apt-get install -y \
    chromium \
    fonts-ipafont-gothic fonts-ipafont-mincho \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

# Set environment variables for Chrome
ENV CHROME_PATH=/usr/bin/chromium
ENV PUPPETEER_EXECUTABLE_PATH=/usr/bin/chromium

# 必要に応じて追加のパッケージをインストール
# RUN apt-get update && apt-get install -y <必要なパッケージ>

# デフォルトのユーザーは node
USER node
