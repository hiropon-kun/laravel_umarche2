## uemy Laravel講座

## ダウンロード方法

git clone

git clone https://github.com/hiropon-kun/laravel_umarche.git

git clone ブランチを指定してダウンロードする場合

git clone -b ブランチ名 https://github.com/hiropon-kun/laravel_umarche.git

もしくはzipファイルでダウンロードしてください

## インストール方法

## インストール後の実施事項

画像のダミーデータは
public/imagesフォルダ内に
sample.jpg ~ sampele6.jpg として
保存しています。

php artisan storage:link で
storageフォルダにリンク後、

storage/app/public/productsフォルダ内に
保存すると表示されます。
(productsフォルダがない場合は作成してください)

ショップの画像も表示する場合は、
storage/app/public/productsフォルダを作成し,
画像を保存してください。
