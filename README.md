# Movie.com DB設計
## usersテーブル
|Colomn|Type|Options|
|------|----|-------|
|name|string|null:false|
|password|string|null:false|
|email|string|nullfalse|
|image|text||


## moviesテーブル
|Colomn|Type|Options|
|------|----|-------|
|name|string|null:false|
|image|text||

## reviewテーブル
|Colomn|Type|Options|
|------|----|-------|
|user_id|integer|null:false,foreign_key: true|
|movie_id|integer|null:false,foreign_key: true|
|text|text|null:false|
