kibana
^^^^^^^^^^^^^^^^^^^^^^^

1. kibana�C���X�g�[��

| playbook���F kibana_site.yml
| �{Playbook��CentOS��kibana���C���X�g�[������ۂɎg�p���܂��B
| �ȉ�������K�v�Ƃ��܂��B
| 

* elasticsearch_url:
        �A�g����elasticsearch��URL���L�ڂ��܂��B


| �T���v��

.. code-block:: none

    elasticsearch_url: "http://localhost:9200"

2. kibana���v���L�V�z���ɗ��p���邽�߂̐ݒ�

| playbook���F config_bihind_proxy.yml
| �{Playbook��CentOS�pkibana���v���L�V�z���ɗ��p���邽�߂̐ݒ���s���ۂɎg�p���܂��B
| �ݒ�ύX�ɂ������Ĉ����͕K�v�Ƃ��܂���B
| 
