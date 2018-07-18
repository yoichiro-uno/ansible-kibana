kibana
^^^^^^^^^^^^^^^^^^^^^^^

1. kibanaインストール

| playbook名： kibana_site.yml
| 本PlaybookはCentOSにkibanaをインストールする際に使用します。
| 以下引数を必要とします。
| 

* elasticsearch_url:
        連携するelasticsearchのURLを記載します。


| サンプル

.. code-block:: none

    elasticsearch_url: "http://localhost:9200"

2. kibanaをプロキシ越しに利用するための設定

| playbook名： config_bihind_proxy.yml
| 本PlaybookはCentOS用kibanaをプロキシ越しに利用するための設定を行う際に使用します。
| 設定変更にあたって引数は必要としません。
| 
