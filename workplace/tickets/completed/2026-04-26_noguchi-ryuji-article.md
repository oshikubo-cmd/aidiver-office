# チケット: 野口竜司さん紹介記事の執筆

- ID: 2026-04-26-001
- 優先度: 高
- ステータス: completed
- 担当者: writer
- 作成日: 2026-04-26
- 完了日: 2026-04-26

## 概要

AI専門家・野口竜司さんの人物紹介記事をAIdiverの記事フォーマットで執筆した。

## 実施内容

1. WebSearch / WebFetch による野口竜司氏のリサーチ
2. `/writer-article_format` スキルに従った2ページ構成の記事執筆（約5,000字）
3. `[要確認]` タグの事実確認（著書発行年・Z AIアカデミア役職・グロースX役職）
4. editorエージェントによる校閲・差し戻し対応
5. 全事実の確認完了・完成稿を保存

## 成果物

- 初稿: `workplace/projects/noguchi-ryuji-article/draft.md`
- 完成稿: `data/documents/2026-04-26_noguchi-ryuji-article.md`

## 確認済み主要事実

| 事実 | 出典 |
|------|------|
| AIX partner株式会社 代表取締役 | 公式サイト |
| 三井住友カード Head of AI Innovation | 公式プレスリリース |
| コクヨ Executive Adviser of AI strategy | 公式プレスリリース |
| 元ELYZA CMO | ELYZAプレスリリース |
| 元ZOZO NEXT 取締役CAIO | PRTIMESプレスリリース |
| 著書『文系AI人材になる』東洋経済新報社 2019年 | Amazon/東洋経済STORE |
| 著書『ChatGPT時代の文系AI人材になる』東洋経済新報社 2023年 | Amazon/東洋経済STORE |
| Z AIアカデミア 発起人 兼 幹事 | EnterpriseZine記事・ZOZO公式 |
| グロースX AI戦略アドバイザー | グロースXプレスリリース |
| JDLA人材育成委員 / FDUA顧問 | 各団体公式サイト |

## 発生した問題と対処

- editorから「Z AIアカデミア発起人」「グロースX AI戦略アドバイザー」の出典不明として差し戻し
  → 追加リサーチで両方を確認・解消

## 再利用可能な学び

[INSIGHT] 人物紹介記事では、引き継ぎ時に「確認済みリスト」を明示してもeditorが独立して検証する。肩書きはすべて出典URLとセットで記録しておくと差し戻しが減る。

[INSIGHT] 役職名は「公式プレスリリース」「団体公式サイト」が最も信頼性が高い。Amazonやメディア記事は補助情報として扱う。
