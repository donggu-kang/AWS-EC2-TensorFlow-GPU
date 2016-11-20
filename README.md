# AWS-EC2-TensorFlow-GPU
TensorFlow on an AWS EC2 Instance with GPU Support
* AWS-EC2
* AWS-Auto Scaling
* TensorFlow
* TensorFlow-GPU
* Python
* linux-ubuntu
* **

들어가기전에
=============

* 이 문서는 AWS(Amazon Web Service)환경에서 TensorFlow 설치방법을 제공하고, 설정을 통해 TensorFlow에서 GPU연산이 가능하도록 시스템을 준비하는 과정이 담겨있다.

* AWS를 사용하여 TensorFlow 환경을 구축하는 이유는, 필요할 때에만 Instance를 Boot 하여 연산을 한 후에 연산이 끝나면 Instance를 Stop 하여 연산으로 인해 발생할 수 있는 운영비용을 최소화 할 수 있고, Auto Scaling을 통해 연산량에 따라 EC2 Instance를 자동으로 확장하고 축소할 수 있는 유연한 환경을 구축하기 위함이다.

* 아래와 같은 내용을 기본적으로 숙지하고 있어야 환경 구축시 여러움이 없을 것 이다.
