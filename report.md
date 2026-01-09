# 情報科学演習IV テーマ2 演習1ログ（B231787 濵田大輔）

---

## 演習1-1（基本操作：add/commit/push）
- 初回コミット：notes.txt / report.md を作成して commit し、GitHubへ push

---

## 演習1-2（差分確認：git diff / git diff --cached）
- notes.txt に line A / line B を追記して差分を確認
```
diff --git a/notes.txt b/notes.txt
index 780b13c..ff01a01 100644
--- a/notes.txt
+++ b/notes.txt
@@ -1 +1,3 @@
 enshu 1-1 start
+line A
+line B
```
