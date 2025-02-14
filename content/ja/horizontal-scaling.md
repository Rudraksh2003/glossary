[ja] Localize Horizontal Scaling                       title: 水平スケーリング
status: Completed
category: コンセプト
tags: ["インフラストラクチャ", "" ,""]
---

## それは何ですか

水平スケーリングは、[ノード](/nodes/) を追加することでシステムの容量を増やす手法です。個々のノードにさらに多くのコンピューティング リソースを追加するのと比べて（後者は[垂直スケーリング](/vertical-scaling/) として知られています）。たとえば、4GB RAM のシステムがあり、その容量を16GB RAM に増やしたいとします。水平方向のスケーリングとは、16GB RAM システムに切り替えるのではなく、4GB RAM を4つ追加することを意味します。

このアプローチでは、新しいインスタンス、つまり[nodes](/nodes/) を追加することでアプリケーションのパフォーマンスが向上します。ワークロードをより適切に分散するため。簡単に言えば、サーバーの負荷を軽減することを目的としています。個々のサーバーの容量を拡張するのではなく、

## 対処する問題

アプリケーションに対する需要が増大し、そのアプリケーション インスタンスの現在の容量を超えると、システムを[スケール](/scalability/)（容量を追加）する方法を見つける必要があります。システムにさらにノードを追加することもできます（水平スケーリング）。またはそれ以上のコンピューティング リソースを既存のノードに追加します（垂直スケーリング）。

## どのように役立つか

水平スケーリングにより、アプリケーションは、基礎となるクラスターが提供する制限に合わせて拡張できます。システムにインスタンスを追加すると、アプリはより多くのリクエストを処理できるようになります。単一ノードが1秒あたり1,000リクエストを処理できる場合、ノードを追加するたびに、リクエストの合計数が1秒あたり約1,000リクエストずつ増加するはずです。これにより、アプリケーションはより多くの作業を同時に実行できるようになります。特にノードの容量を増やす必要はありません。

## 関連用語

* [垂直スケーリング](/vertical-scaling/)
* [オートスケーリング](/auto-scaling/)
