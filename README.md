# isucon13
## ビルド
```bash
cd webapp/go/
go build -o isupipe && sudo systemctl restart isupipe-go.service
```
## ログ
```bash
# リアルタイム表示
sudo journalctl -f isupipe-go.service

# 末尾から30行表示
sudo journalctl -n 30
```
[【2023年1月版】 journalctl 覚えておきたい使い方メモ #Linux - Qiita](https://qiita.com/nouernet/items/c60ff2621385f4d8f7b6#%E4%B8%BB%E8%A6%81%E3%81%AA%E3%82%AA%E3%83%97%E3%82%B7%E3%83%A7%E3%83%B3)
