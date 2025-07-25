---
icon: chevron-down
---

# 2.3 クライアント管理

<figure><img src="../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**機能説明：**

この「クライアント管理」画面は、エンドユーザーが自身のPCにインストールして使用するデスクトップクライアントアプリケーション（Windows版、Mac版など）のバージョン管理と配布を行うための、**システム提供者（スーパー管理者）専用の機能**です。

この画面では、各プラットフォーム（Windows, Mac）ごとに公開されているクライアントのバージョン情報が一元管理されています。リストには、バージョン番号、内部的な迭代ID（イテレーションID）、強制アップグレードの要否、アップグレード内容（リリースノート）、プラットフォーム種別、そしてインストーラーのダウンロードアドレスといった詳細情報が表示されます。



**中核的な役割 ：**

この機能の主な役割は、クライアントソフトウェアのライフサイクル全体を管理し、統制することです。その中核的な目的は以下の通りです。

1. **ソフトウェアリリース管理 (Software Release Management):**\
   新しい機能の追加やバグ修正が行われたクライアントの新バージョンを、安全かつ確実に全ユーザーへ公開するためのコントロールパネルとして機能します。
2. **強制アップグレード制御 (Forced Upgrade Control):**\
   重大なセキュリティ脆弱性の修正や、サーバーとの互換性を維持するために不可欠なアップデートがあった場合に、「強制アップグレード」を「是（はい）」に設定することで、全ユーザーにアップデートを必須とさせることができます。これにより、ユーザー環境の安全性と機能の統一性を確保します。
3. **一元的な配布管理 (Centralized Distribution Management):**\
   公式のインストーラーダウンロードURLをこの管理画面で一元管理することにより、ユーザーが常に正規の、安全なソフトウェアを入手できることを保証します。
