# AWS-EC2-TensorFlow-GPU
TensorFlow on an AWS EC2 Instance with GPU Support
* AWS-EC2
* AWS-Auto Scaling
* TensorFlow
* TensorFlow-GPU
* Python
* linux-ubuntu

***

들어가기전에
=============

* 이 문서는 AWS(Amazon Web Service)환경에서 TensorFlow 설치방법을 제공하고, 설정을 통해 TensorFlow에서 GPU연산이 가능하도록 시스템을 준비하는 과정이 담겨있다.

* AWS를 사용하여 TensorFlow 환경을 구축하는 이유는, 필요할 때에만 Instance를 Boot 하여 연산을 한 후에 연산이 끝나면 Instance를 Stop 하여 연산으로 인해 발생할 수 있는 운영비용을 최소화하고, Auto Scaling을 통해 연산량에 따라 EC2 Instance를 자동으로 확장하고 축소할 수 있는 유연한 환경을 구축하기 위함이다.

* 처음부터 높은 사양의 Instance를 사용하여 구축하게되면 많은 비용이 청구될 수 있다. AWS는 사용시간에 따른 과금제도 이므로, 연산이 끝나면 Instance를 꼭 Stop 시키길 바란다.

* AWS 사용으로 인한 비용이나 과금, 데이터망실 등의 모든 법적책임은 사용자에게 있다.
