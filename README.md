elasticsearch_url: "http://localhost:9200"
need_local_volume: "yes"
localvolumes:
  - /data/kibana/data
  - /data/kibana/conf
  - /data/kibana/log

containersettings:
 - {"container_name": "kibana01", "container_image": "centos", "container_ports": [ "5601:5601"], "container_volumes": [ "/data/kibana/conf:/etc/kibana", "/data/kibana/data:/var/lib/kibana", "/data/kibana/log:/var/log/kibana"]}
