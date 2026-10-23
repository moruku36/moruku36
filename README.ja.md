# 森 健太郎

[English](README.md) | [日本語](README.ja.md)

クラウド、AI、セキュリティ領域で、実践的な検証と制作を行い、その過程を記録しています。  
実環境を意識したアーキテクチャ、AI活用ワークフロー、セキュリティ技術を、実装とテストを通じて検証することを重視しています。

## AI・クラウド・セキュリティの制作物

### AIワークフロー

- [Local AI Sidekick](https://github.com/moruku36/local-ai-sidekick) — 作業範囲を限定したローカルOllamaコーディングワーカー。変更はリードAIのレビューに戻します。[実GPUを使ったE2E検証](https://github.com/moruku36/local-ai-sidekick/pull/16)は合成リポジトリで成功しました。本番運用は未検証です。
- [AI Governance Control](https://github.com/moruku36/ai-governance-control) — タスク成果物の確認と人による承認を記録する**MANUAL_ONLYの実験**。[状態通知の内容契約](https://github.com/moruku36/ai-governance-control/pull/49)は送信機能を含まず、マージとデプロイは人が判断します。
- [Multi-cloud SRE Agent Research](https://github.com/moruku36/multicloud-sre-agent-survey-2026) — 出典付きの調査と、AWS・Azure・Google Cloudの模擬応答を使う[パッケージ済みオフライン合成デモ](https://github.com/moruku36/multicloud-sre-agent-survey-2026/pull/5)。実行と復旧確認は未実施で、実クラウドの修復も検証していません。

### クラウド検証

- [Level 2: マルチクラウドセキュリティ検証](https://github.com/moruku36/cloud-validation-level2-multicloud)と[Level 3: クラウドセキュリティ・アーキテクチャ検証](https://github.com/moruku36/cloud-validation-level3-architect) — Level 2ではTerraformによる基盤検証、Level 3では設計判断とコスト・リスク評価を記録。検証範囲は各リポジトリで確認できます。
- [OCI Validation Lab](https://github.com/moruku36/oci-validation-lab) — 基礎学習とオフラインモデル。[限定的なOCI Console演習](https://github.com/moruku36/oci-validation-lab/pull/2)では一時的なVCNとプライベートサブネットを作成・削除しました。Level 1の修了とTerraformの実環境適用は未検証です。

### 防御的セキュリティ

- [Personal Security Auditor](https://github.com/moruku36/personal-security-auditor) — 秘密の値を収集せず、端末の一部の設定を確認するローカルCLI。[読み取り専用のLinux対応](https://github.com/moruku36/personal-security-auditor/pull/9)には合成テストがありますが、Linux実機での検証は未実施です。
- [Web Security Control Lab](https://github.com/moruku36/web-security-control-lab) — localhost限定の学習用ラボ。脆弱・対策済みの2モードで6つのWeb制御を観察、スキャン、修正、再確認します。対策済みモードは本番環境の安全性を保証しません。

## 調査・サーベイ・レポート

制作物に加えて、独自調査、技術サーベイ、分析レポートを継続的に公開・更新しています。

- [2026 Company Analysis](https://github.com/moruku36/nri-2026-company-analysis) — 企業分析と調査記録。
- [Security Landscape 2026](https://github.com/moruku36/security-landscape-2026) — セキュリティ技術・業界動向の調査。
- [Independent CS Research 2026](https://github.com/moruku36/independent-cs-research-2026) — コンピュータサイエンス分野の独立した調査・サーベイ記録。

完成度や運用状況はリポジトリごとに異なります。インフラの再構築やAIワークフローの実行前に、各READMEにある現在の状態と制約を確認してください。

発信先: [Zenn](https://zenn.dev/kentaro36) · [DEV Community](https://dev.to/moruku36) · [LinkedIn](https://www.linkedin.com/in/kentaro-mori-4592a1169/)。
