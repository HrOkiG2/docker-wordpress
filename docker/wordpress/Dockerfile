# 公式のWordPressイメージをベースに使用
FROM wordpress:php8.3-apache

# Node.js（バージョン20以上）をインストール
RUN curl -sL https://deb.nodesource.com/setup_20.x | bash - \
    && apt-get update \
    && apt-get install -y nodejs

# 作業ディレクトリを設定
WORKDIR /var/www/html

# コンテナ起動時に実行するコマンドを設定（Apacheサーバーを起動）
CMD ["apache2-foreground"]
