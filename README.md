# Spring Bootの起動
```bash
cd backend
bash ./gradlew bootRUN
```

# 間違えてローカルリポジトリにて`main`にコミットしてしまったら、、、
```bash
$ git log
```

間違えてmainにコミットしてしまったログのハッシュ値をコピー

```bash
$ git revert <ハッシュ値>
```
参考

[Qiita](https://qiita.com/Ayumu-y/items/89bf8a91c048734d827e)
