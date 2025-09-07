---
title:          "GeoGauss: Strongly Consistent and Light-Coordinated OLTP for Geo-Replicated SQL Database"
date:           2023-06-23 00:01:00 +0800
selected:       true
pub:            "Proceedings of the International Conference on Management of Data (SIGMOD)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2023"

abstract: >-
  In this work, we propose a strongly consistent OLTP database GeoGauss with full replica multi-master architecture. To efficiently merge the updates from different master nodes, we propose a multi-master OCC that unifies data replication and concurrent transaction processing. By leveraging an epoch-based delta state merge rule and the optimistic asynchronous execution, GeoGauss ensures strong consistency with light-coordinated protocol and allows more concurrency with weak isolation, which are sufficient to meet our needs 
cover:          /assets/images/covers/sigmod-geogauss.png
authors:
  - "<b style='font-weight:900;color:#000;'>Weixing Zhou*</b>"
  - Qi Peng
  - Zijie Zhang
  - Yanfeng Zhang*
  - Yang Ren
  - Sihao Li
  - Guo Fu
  - Yulong Cui
  - Caiyi Wu
  - Shangjun Han
  - Shengyi Wang
  - Guoliang li
  - Ge Yu
links:
  Code: https://github.com/iDC-NEU/GeoGauss
  Slides: https://idc-neu.github.io/slides/GeoGauss_SIGMOD23.pdf
  Video: https://idc-neu.github.io/videos/GeoGauss_SIGMOD23.mp4
---




