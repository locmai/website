---
title: Cluster
id: cluster
date: 2019-12-16
full_link:
short_description: >
  Một tập các máy tính, được gọi là nodes, thực hiện việc chạy các ứng dụng đã được container-hóa và quản lý chúng với Kubernetes. Một cluster có ít nhất một worker node và ít nhất một master node.

aka:
tags:
  - fundamental
  - operation
---

Một tập các máy tính, được gọi là nodes, thực hiện việc chạy các ứng dụng đã được container-hóa và quản lý chúng với Kubernetes. Một cluster có ít nhất một worker node và ít nhất một master node.

<!--more-->

Worker node host các pods là những thành phần của một ứng dụng. Master node quản lý các worker nodes và các pods trong một cluster. Sử dụng nhiều hơn một master node nhằm mục đích cung cấp cho cluster khả năng chuyển đổi sang máy dự phòng (failover) và tính sẵn sàng cao (high availability)
