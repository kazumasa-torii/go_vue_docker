# カミナシ - ソフトウェアエンジニア選考課題のご案内

## 本課題の意図・位置付け

本課題は、候補者さまの技術力や知識、加えて技術的な思想やご志向と当社とのフィットを確認させていただく目的で設定しております。

## 課題テーマ

Twitter クローンの開発  
※ Twitter API クライアントの開発ではなく、サービスとしての Twitter のクローンを開発する課題です

## 課題提出先

課題の開発作業と成果物の提出には、本リポジトリをご利用いただきます。

- 課題に関するご質問は、GitHub Discussions にてご連絡ください。
- 課題完成時には当社採用担当までその旨ご連絡をお願いいたします。

## 課題提出期限

当社採用担当からの選考課題案内を起点として、おおむね1週間程度での提出を目安としています。

一方で、当社は候補者さまの多くが普段の業務と並行して技術課題に取り組んでくださっていることを認識しており、『1週間程度』はあくまでも目安としての設定です。状況に応じて1週間を超えることは全く問題ありませんので、その場合は提出時期の目処について当社採用担当までご一報をお願いいたします。

## 課題内容

### 利用技術

- [Go 言語](https://go.dev/)を利用して開発してください。
- Web フロントエンドの言語、実装方式の指定はありません。
  - Web ページのレンダリングについても、サーバーサイド側での出力や [SPA](https://developer.mozilla.org/en-US/docs/Glossary/SPA) など、候補者さまご自身の好む方式にて実装してください。

### 機能要件

1. ツイートする
2. 他ユーザーをフォローする
3. タイムラインを見る

- 上記要件を満たした上でのさらなる追加機能実装については、一切制約はございません。
- 最終的な成果物、あるいは実装過程にて、ぜひ候補者さまご自身の知識や経験、考え方を表現してください。

### 留意事項

- 事業会社において複数名からなるエンジニアリングチームで開発運用していくことを前提としたアウトプット品質を意識してください。
  - e.g. チームメイトが開発運用に参加するための情報が README に書かれている、など
- コードやドキュメントの変更履歴も選考審査における重要な情報となります。候補者さまご自身の作業の流れが可能な限りそのままコミットログとして残る形で課題に取り組んでいただけることを期待しております。
- デプロイできる状態でご提出ください。
  - 実際にデプロイされている必要はありません。
- 多くの候補者さまが普段の業務と並行して当社技術課題に取り組んでいただいていることに心から感謝します。もしも時間の都合上やり残したことがあるまま提出せざるを得ない場合は、ぜひそれらのやり残した事柄を README にご記載ください。選考審査プロセスにてあわせて参考にさせていただきます。

## 主な確認ポイント

- 課題の要件機能がすべて実装されており、それらが問題なく動作すること
  - 審査プロセスは `main` ブランチで実施されます。
  - `main` 以外のブランチで開発作業を実施する場合、提出前にすべての成果物が `main` ブランチで正しく動作することをご確認ください。
- 設計や実装上の技術的想定
- 要件外で取り組まれた内容