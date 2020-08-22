# Light LEMONADE

Efficient Multi-objective Neural Architecture Search via Lamarckian Evolution[1]에 제안된 LEMONADE (Larmarckian Evolutionary algorithm for Multi-Objective Neural Architecture DEsign) 알고리즘을 작은 스케일로 재구현한 Light LEMONADE 코드입니다. 

### 요약 
Evolutionary algorithm으로 Neural Architecture Search를 수행합니다. Multi-objective로써, validation loss는 최소화하면서 parameter 개수도 최소화하는 모델을 찾고자 합니다. Object 간 trade-off가 존재하기 때문에 pareto front를 추정하여 제공합니다.
 
### 개발 환경
Language : Python

Deep learning Library : Tensorflow Keras

Google Colab 환경에서 개발하였습니다.

알고리즘에 대한 자세한 설명은 프로젝트 보고서 [https://github.com/MY-Park/Light-LEMONADE/blob/master/term_project_report_20203758.pdf](https://github.com/MY-Park/Light-LEMONADE/blob/master/term_project_report_20203758.pdf)를 확인해주세요.

## References

[1] Efficient Multi-objective Neural Architecture Search via Lamarckian Evolution, Thomas Elsken et al. (ICLR 2019)

[2] Fashion-MNIST dataset (https://github.com/zalandoresearch/fashion-mnist)


