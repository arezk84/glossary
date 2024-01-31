---
title: ベアメタルマシン
status: Completed
category: テクノロジー
tags: ["インフラストラクチャー", "", ""]
---

ベアメタルとは物理コンピューターを意味し、具体的にはサーバーのことでありオペレーティングシステムが1つしかないものです。最近のコンピューティングでは、サーバーの多くが[仮想マシン](/ja/virtual-machine/)であるため、この区別は重要です。物理サーバーは、一般的に強力なハードウェアを内蔵したかなり大型のコンピューターです。[仮想化](/ja/virtualization/)せずに、物理ハードウェア上にオペレーティングシステムをインストールし直接アプリケーションを実行することを"ベアメタル"上で実行すると呼ばれます。

## 解決すべき問題はなんですか

1つのオペレーティングシステムと1台の物理コンピューターの組み合わせはコンピューティングの原型です。物理コンピューターのすべてのリソースがオペレーティングシステムで直接利用可能であり、仮想化レイヤーが存在しないため、オペレーティングシステムの命令をハードウェアに変換する際に人工的な遅延が発生しません。

## どのように役に立つのでしょうか

コンピューターのすべての計算リソースを単一のオペレーティングシステムに割り当てることで、オペレーティングシステムに最高のパフォーマンスを提供できる可能性があります。ハードウェアリソースに極めて高速にアクセスしなければならないワークロードを実行する必要がある場合、ベアメタルが適切なソリューションかもしれません。

[クラウドネイティブアプリケーション](/ja/cloud-native-apps/)のコンテキストでは、私たちは一般的にパフォーマンスを、[水平スケーリング](/ja/horizontal-scaling/)（リソースプールにマシンを追加する）で処理できる多数の並行イベントへの[スケーリング](/ja/scalability/)という観点から考えます。しかし、ワークロードによっては[垂直スケーリング](/ja/vertical-scaling/)（既存の物理マシンにさらにパワーを追加する）が必要な場合や、極めて高速な物理ハードウェアのレスポンスが必要になる場合はベアメタルが適しています。また、ベアメタルにおいては、タスクを達成するために、物理ハードウェアや場合によってはハードウェアドライバをチューニングすることもできます。