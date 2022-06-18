# Deep Continuous Prompt for Contrastive Learning of Sentence Embeddings (리뷰)
SimCSE와 Prefix-Tuning을 합친 연구. 혼자 SimCSE를 구현하던 중, GPU 메모리가 부족하여 Large Batch를 사용할 수 없어 고민하다가 Prefix-Tuning을 적용해 보기로 마음먹었음. 혹시나 이런 연구가 있을까 찾아보니 역시나 존재하였음..! 논문 상으로는 오히려 기존 SimCSE를 뛰어넘는 SOTA의 성능을 보이며 공식 GitHub도 존재함. 그러나 (22년 6월 현재) 직접 구현한 성능은 매우 좋지 않음.. 공식 GitHub 코드를 돌려볼 수 있겠으나, ACL에서 리젝 당한 것으로 추정되는 것 포함 여러 미심쩍은 부분들이 존재하여 이쯤하고 접어두려 함. (회사 일이 아닌 개인 토이 프로젝트이므로..)<br/><br/>
References:
* [DCPCSE](https://arxiv.org/abs/2203.06875)
* [Prefix-Tuning](https://arxiv.org/abs/2101.00190)
* [개인 Prefix-Tuning 토이 프로젝트](https://github.com/ChainsmokersAI/Controlled-Prefix-Tuning)

