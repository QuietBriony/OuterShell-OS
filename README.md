# Landscape-OS

Landscape-OS は、
造園業務・緑化コンサル・行政インフラを対象とした
**造園DXのためのロジック／DB／自動化エンジン群** を管理するリポジトリである。

本リポジトリは「実装層」であり、
業務データや成果物は一切置かない。

---

## ■ 全体構成における位置づけ

Landscape-OS は、以下3ストレージ構成の一角を担う。

- SharePoint  
  → 正式業務データ／成果物／案件運用（正史）
- Dropbox  
  → 写真・動画・外部資料・雑インプット
- GitHub（本リポジトリ）  
  → ロジック／DB／自動化コード（実装層）

---

## ■ このリポジトリに置く予定のもの（将来）

- 歩掛DB（JSON / Schema）
- 樹種DB・害虫DB（JSON）
- 造園QAエンジン用データ
- SharePoint / Dropbox を操作する自動化ロジック
- Webベースの造園DXツール（HTML / JS）

※ いずれも **SharePointでの運用が安定した後に移植**する。

---

## ■ 置かないもの（原則）

- 契約書・図面・写真
- Excel / Word / PDF の業務成果物
- 代理人が作成した生データ

それらはすべて SharePoint / Dropbox 側で管理する。

---

## ■ 運用ポリシー

- 仕様が固まってから実装する
- 業務フローが変わったら、まず SharePoint 側を更新
- GitHub は「最後に置く場所」

---

## ■ 将来展開（想定）

- 組合向け共通DB
- 他社展開可能な造園DXテンプレ
- 行政・緑化コンサル向け解析基盤
- ChatGPT / PowerAutomate 連携エンジン

---

This repository is intentionally minimal at present.
Implementation will begin after operational stabilization.
