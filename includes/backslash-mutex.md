---
ms.openlocfilehash: c28e3f97e02079905d591a7f27dc8d68d603c0bf
ms.sourcegitcommit: 1bb00d2f4343e73ae8d58668f02297a3cf10a4c1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/15/2019
ms.locfileid: "63871563"
---
円記号 (\\) は、ミューテックス名の予約文字です。 ターミナル サーバー セッションのミューテックス使用に関する注記に指定されていない限り、ミューテックス名に円記号 (\\) を使用しないでください。 使用した場合、ミューテックスの名前が既存のファイルを表すとしても、<xref:System.IO.DirectoryNotFoundException> がスローされることがあります。
