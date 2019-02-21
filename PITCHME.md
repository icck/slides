### Introduction of Rancher
2019/02/21 komori issei

---
#### Agenda

- What's Docker? |
- What's Kubernetes? |
- What's Rancher? |
- Rancher Demo |

---

![alt](assets/Docker.png)

---

#### What's Docker?
- About
  - コンテナ型の仮想環境を作成、配布、実行するためのプラットフォーム |

+++

#### What's Docker?
~~~
  ------------------------
  | Container | Container |
  ------------------------
  |     Docker Engine     |
  ------------------------
  |       Host OS         |
  ------------------------
~~~

---

![alt](assets/k8s.png)

---

#### What's Kubernetes?
- About
  - Google社内のオーケストレーションシステムからインスパイアされて作成されたOSSの「コンテナオーケストレーションツール」 |
  - クーバーネーティス、クーバネィティス、クバネティスetc.. |
  - k8s |

+++

#### What's Kubernetes?
- 役割
  - コンテナのスケジューリング |
  - ローリングアップデート |
  - オートスケーリング |
  - 死活監視 |
  - コンテナーの自動回復 |
  - サービスディスカバリ |
  - ロードバランシング |
  - ログ管理 |

+++

#### What's Kubernetes?
- 実現
  - 頻繁なアプリケーションのデプロイを可能にするシステム基盤 |
  - 無停止リリース、高可用性なシステム基盤 |
  - 負荷に応じた伸縮自在なシステム基盤 |

+++

#### What's Kubernetes?
 - 知らない間に使ってます
+++
![alt](assets/pokemongo.png)
+++
![alt](assets/abematv.png)
+++
![alt](assets/merukari.png)


---

![alt](assets/rancher-logo-horiz-color.png)

---

### What's Rancher?
- About
  - コンテナ環境の構築・運用するための統合管理プラットフォーム |
  - オンプレ＆クラウドどちらでも利用可能 |
  - ホストとコンテナの管理 |
  - アプリケーションのデプロイ |
  - オーケストレーション環境の自動構築 |
  - Rancher Labが開発,OSS |
  - 有償サポートのビジネスモデル |
  - 100% Kubernetes |
  - Golang,etcd |

+++

### What's Rancher?
- Feature 2.X
  - One Click Deployment!! |
    - 強力なカタログ一覧から簡単にデプロイ
  - Creating Private Catalog!! |
    - オリジナルカタログも登録可能

+++
### What's Rancher?
1. Run Rancher Container!!

~~~
$ sudo docker run -d --restart=unless-stopped -p 80:80 -p 443:443 rancher/rancher
~~~

2. Access!!

~~~
https://EXTERNAL-IP/
~~~



---

### Rancher Demo

---

