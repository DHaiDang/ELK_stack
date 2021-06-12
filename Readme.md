# Install elk stack


usesage : doker-compose up 

Elasticsearch:
    - Version : ${ELK_VERSION}
    - Volume mount point với data của elasticsearch -> sử dụng cho việc chia sẻ data giữa các nodes
    - 