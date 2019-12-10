---
title: 一般的な毎月の課金シナリオ |パートナーセンター
ms.topic: article
ms.date: 11/25/2019
description: 毎月の課金 (新しいサブスクリプションの追加、ライセンス数の変更、サブスクリプションの中断など) を使用する場合の、パートナーセンターでの一般的なシナリオ。
ms.assetid: ''
author: MaggiePucciEvans
ms.author: evansma
Keywords: 課金、支払い、注文、使用状況、月単位の課金、サブスクリプション、調整ファイル
ms.localizationpriority: medium
ms.openlocfilehash: 9cae4f82e059a2c8258a00ae51a406ca890f7a67
ms.sourcegitcommit: c793c1b61f50fc0b0a12c95cedd9f57b31703093
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/03/2019
ms.locfileid: "74722486"
---
# <a name="monthly-billing-scenarios"></a>毎月の課金シナリオ

**適切なロール**

- 管理エージェント
- 課金の管理
- ヘルプデスク エージェント
- 販売代理店

この例の[一般的な課金シナリオ](common-billing-scenarios.md)は、パートナーセンターで毎月の課金を使用する場合に適用されます。

## <a name="new-monthly-subscription"></a>新しい月額サブスクリプション

請求日は毎月 15 日です。 1 月 13 日に、4ドル/月のライセンスを 1 つ含む新しいサブスクリプションを購入し、月次請求を選択しました。 1 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|2018/1/13         |2018/2/12    |Cycle fee   |4.00       |1        |4.00 |

2 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|2018/2/13         |2018/3/12    |Cycle fee   |4.00       |1        |4.00 |

## <a name="change-license-quantity"></a>ライセンス数の変更

請求日は毎月 15 日です。 1 月 13 日に、4ドル/月のライセンスを 1 つ含む新しいサブスクリプションを購入し、月次請求を選択しました。 1 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|2018/1/13         |2018/2/12    |Cycle fee   |4.00       |1        |4.00    |

2 月 1 日、ライセンスの数を 1 から 2 に増やします。 2 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
| 2018/1/13        |2018/2/12    |Cycle Instance Prorate (サイクル インスタンスの日割り料金)   |-4.00       |1        |-4.00   |
|2018/1/13         |2018/1/31    | Cycle Instance Prorate (サイクル インスタンスの日割り料金)   |2.45       |1        |2.45    |
|2018/2/1         |2018/2/12    | Cycle Instance Prorate (サイクル インスタンスの日割り料金)   |1.55       |2        |3.10    |
|2018/2/13         |2018/3/12    | Cycle Instance Prorate (サイクル インスタンスの日割り料金)   |4.00       |2        |8.00    |

月額料金は 4.00 で、サービス期間 2018/1/13 ～ 2018/2/12 には 31 日間あります。 これは、1 日あたりの価格 0.129 (4/31) に相当します。

日割り計算期間 2018/1/13 ～ 2018/1/31 には 19 日間あります。

日割り単価 = 2.451 = 19 x 0.129

日割り計算期間 2018/2/1 ～ 2018/2/12 には 12 日間あります。

日割り単価 = 1.54 = 12 x 0.129

## <a name="suspend-before-30-days"></a>30日前に中断

請求日は毎月 15 日です。 1 月 13 日に、4ドル/月のライセンスを 1 つ含む新しいサブスクリプションを購入し、月次請求を選択しました。 1 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|2018/1/13         |2018/2/12    |Cycle fee   |4.00       |1        |4.00    |

2 月 1 日、サブスクリプションを中断します。 2 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
2018/1/13|2018/2/12|Cancel Fee (取り消し料金)|-4.00|1|-4.00

## <a name="suspend-after-30-days"></a>30日後に中断

請求日は毎月 15 日です。 1 月 13 日に、4ドル/月のライセンスを 1 つ含む新しいサブスクリプションを購入し、月次請求を選択しました。 1 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
2018/1/13|2018/2/12|サイクル料金|4.00|1|4.00

2 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
2018/2/13|2018/3/12|サイクル料金|4.00|1|4.00

3 月 1 日、サブスクリプションを中断します。 3 月 15 日、ライセンスベースの調整ファイルに次の請求行が追加されます。

|請求開始日 |請求終了日 |請求の種類 |単価 |Quantity |Amount |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
2018/3/1|2018/3/12|Cancel Fee (取り消し料金)|-1.72|1|-1.72

月額料金は 4.00 で、サービス期間 2018/2/13 ～ 2018/3/12 には 28 日間あります。 これは、1 日あたりの価格 0.143 (4/28) に相当します。

単価 = サービス期間の日数 x 1 日あたりの価格 x ライセンス数

取り消し期間 2018/3/1 ～ 2018/3/12 には 12 日間あります。

したがって、単価 = -1.716 (12 x 0.143 x (-1)) です。