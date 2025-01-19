# local環境構築手順

## 各アプリのクローン

### laravel-11-react
```
git clone git@github.com:reonotis/laravel-11-react.git
```

## コンテナ作成
```
docker compose build
docker compose up -d
```
## 各アプリの初期設定
### laravel-11-react
```
docker exec -it laravel_11_react_app bash
composer install
npm run build
```
