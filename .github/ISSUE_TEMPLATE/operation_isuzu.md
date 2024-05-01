---
name: 神奈中バス定期追加(いすゞ従業員向け)
about: いすゞ従業員様向けに神奈中バスの企業定期券を付与する
title: 神奈中様いすゞ向け企業定期券 2024年X月分付与
labels: operation, isuzu
assignees: kayo311
---

## ✨ 概要

神奈中様向けにいすゞ定期券を追加、更新、停止する
期間 2024//01 - 2024//31(1,3,6ヶ月分)

## 📅 スケジュールと期限

- [ ] /18(木) 申請フォーム公開
- [ ] /25(木）申請フォームクローズ
- [ ] /26(金）突合確認
- [ ] /30(火) 定期券配布
- [ ] /1(月) 定期券停止

## ✔️ 確認事項
- [ ] 本番環境の最新 dump データでテストしているか

**新規追加**
- [ ] 新規追加リストの xls で数字と文字列の書式の違いで省かれている人がいないか
- [ ] 新規追加の付与月数
- [ ] 管理画面での確認
- [ ] 作業前後でのアクティブな定期券の数

**停止リスト**
- [ ] 管理画面での確認
- [ ] 作業前後でのアクティブな定期券の数

## 📚過去の Issue
| 年 | 1月 | 2月 | 3月 | 4月 | 5月 | 6月 | 7月 | 8月 | 9月 | 10月 | 11月 | 12月 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 2024 | https://github.com/ryde-inc/ryde-pass/issues/1411 | https://github.com/ryde-inc/ryde-pass/issues/1459 | https://github.com/ryde-inc/ryde-pass/issues/1475 | https://github.com/ryde-inc/ryde-pass/issues/1569
| 2023 | - | https://github.com/ryde-inc/ryde-pass/issues/912 | - | https://github.com/ryde-inc/ryde-pass/issues/1054 |  https://github.com/ryde-inc/ryde-pass/issues/1089 | https://github.com/ryde-inc/ryde-pass/issues/1108 | https://github.com/ryde-inc/ryde-pass/issues/1175 | https://github.com/ryde-inc/ryde-pass/issues/1210 | https://github.com/ryde-inc/ryde-pass/issues/1253 | https://github.com/ryde-inc/ryde-pass/issues/1305 | https://github.com/ryde-inc/ryde-pass/issues/1366 | https://github.com/ryde-inc/ryde-pass/issues/1390

## ☕ 補足

[マニュアル](https://www.notion.so/rydeinc/a72b342a93a44e11ab970ecac26a082f)
[作業 Drive](https://drive.google.com/drive/u/0/folders/17VQgdSbTjF0hzMnpOWK3QzIB9-GDIV7I)

- **pass_period(期間->開始日)** id: 68(1 ヶ月->その他), 69(3 ヶ月->5/1,11/1), 70 (6 ヶ月->2/1,8/1)
- **pass_type** id: 28, name: 'いすゞ藤沢工場 従業員様向け'
- **pass_group** id: 8, name: '神奈川中央交通'

## 実施コマンド
[新規付与](https://www.notion.so/rydeinc/_-0cda9ac819554577b5edff35608e0ee6)
[停止](https://www.notion.so/rydeinc/_-5243df0e2a6a44248b7811b8615afdfa)