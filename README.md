# plutarch
cat > README.md <<'EOF'
# Plutarch

> Parallel lives of your team — チームの一人ひとりに、列伝を持つ。

マネージャーがチームメンバー一人ひとりの強み・動機・コンディションを言語化し、
それに合ったコミュニケーションと任せ方へ翻訳するためのノートツール。

## 公開URL

https://takayuki-iida.github.io/plutarch/

## 使い方

ブラウザで上記URLを開くだけ。データはブラウザのlocalStorageに保存される。

## 機能制限

`時間配分`・`タスク`・`Slack分析` の更新機能は Claude アーティファクト内でのみ動作。
日常の編集はホスト版で、シグナル更新は Claude 経由 → エクスポート/インポートで運用。
EOF
