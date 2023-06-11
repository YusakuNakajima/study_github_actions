## 概要
- unit test、integrated testなどのテスト系をやったことがないのでその練習
- テストやビルドを自動化して開発効率を高める(CI/CD)の練習
  - github actionsを用いる

## モチベ
- ROSの環境構築、プログラム作成を常に動く環境に保つのが大変すぎるので、手間はかかるけどユニットテストとCIくらいは導入したい
  - ダメになったら使い捨てもできるくらい気軽に環境構築できるようにが目標
- テストにはpython標準のunittestもしくはpytest、CI/CDにはgithub actionsを使う

### 最低限以下を目指す
  - パッケージごとの分散リポジトリにしてgithub actionsで自動ビルド
  - プログラムにはユニットテストを書いてgithub actionsで自動ユニットテスト
### できれば以下もやりたい
  - 必要な全てのパッケージを取り込んだ自動総合ビルドテスト
  - 各プログラム間の連携も含めた統合テスト、総合テスト
## 参考
[unit testのチュートリアル](https://qiita.com/phorizon20/items/acb929772aaae4f52101)
[github actionsのチュートリアル](https://zenn.dev/hashito/articles/7c292f966c0b59)
[python標準のunittestの解説](https://www.mathkuro.com/python/unittest/)
