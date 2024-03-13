## 概要

静的ファイルを格納するS3バケットとそれをオリジンとしたCloudFrontを作成します

また、basic認証用のCloudFront Function も合わせて作成します

## Basic認証用パスワード生成コマンド

ID: testUser
Password: testPassword

注: 

```bash
echo -n "testUser:testPassword" | base64
```

## 補足: What is Basic auth

HTTPで定義される認証方式（HTTP認証）の一つ。

RFCは下記

[The 'Basic' HTTP Authentication Scheme](https://datatracker.ietf.org/doc/html/rfc7617#section-2.1)
