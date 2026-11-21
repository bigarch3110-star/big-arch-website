# BIG ARCH 追加ページ更新セット（2026-11-22）

既存のトップページ index.html を上書きしない、安全な追加セットです。

## ファイル
- history.html：3世代の歴史と真也監督の年表
- riders.html：蓮・琉生の紹介
- team.html：監督・BIG ARCH号・SEVEN・サポート状況
- secret.html：漫画風の裏ページ
- assets/style.css：共通デザイン
- assets/bloodline-poster.png：裏ページのポスター

## 更新手順
1. ZIPを解凍。
2. GitHubの bigarch3110-star/big-arch-website を開く。
3. Code → Add file → Upload files を選ぶ。
4. ZIPそのものではなく、解凍したHTML 4ファイルとassetsフォルダをアップロード。
5. Commit changes を押す。
6. Pagesの公開元が main / (root) なら、公開サイトの /history.html /riders.html /team.html /secret.html に反映。
7. トップページからリンクさせるには既存 index.html に以下を追加：
   <a href="history.html">HISTORY</a>
   <a href="riders.html">RIDERS</a>
   <a href="team.html">TEAM</a>
   <a href="secret.html">SECRET ARCHIVE</a>

注意：既存assets/style.cssがある場合、上書き前に内容を確認してください。既存サイトに同名のファイルがある場合も同様です。
未成年の個人情報や許諾のない企業ロゴ、雑誌の誌面写真、ナンバープレートは無断公開しないでください。
