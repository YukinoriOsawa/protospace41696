# テーブル設計

## users テーブル

| Column             | Type   | Options     |
| ------------------ | ------ | ----------- |
| email              | string | null: false, unique: true |
| encrypted_password | string | null: false |
| name               | string | null: false |
| profile            | string | null: false |
| occupation         | string | null: false |
| position           | string | null: false |

## commentsテーブル

| Column | Type   | Options     |
| ------ | ------ | ----------- |
| 　　　   | string | null: false |

## prototyesテーブル

| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| 　　　　　  | references | null: false, foreign_key: true |
| 　　　  | references | null: false, foreign_key: true |

