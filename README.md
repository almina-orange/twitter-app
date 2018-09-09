# twitter-app

## Info
* Simple Twitter App
* Twitter-API 学習用レポジトリ

## Usage
* アクセス情報を`config.py`として作成する

    ```python
    # config.py
    CONSUMER_KEY = "**************"
    CONSUMER_SECRET = "**************"
    ACCESS_TOKEN = "**************"
    ACCESS_TOKEN_SECRET = "**************"
    ```

Note
* 各エンドポイントにはリクエスト回数に制限がある
* リクエスト回数の確認もプログラムで可能（`requests.py`を参照）

## Ref
* PythonでTwitter API を利用していろいろ遊んでみる - Qiita, [https://qiita.com/bakira/items/00743d10ec42993f85eb](https://qiita.com/bakira/items/00743d10ec42993f85eb)