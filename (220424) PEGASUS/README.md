# PEGASUS: Pre-training with Extracted Gap-sentences for Abstractive Summarization (리뷰)
Abstractive Summarization 수행을 목적으로 하는 Pre-Trained LM. 입력 문서의 중요한 문장을 통으로 Masking한 후, 주위 문장들을 참조하여 해당 문장을 복원하는 Gap Sentences Generation (GSG)을 Pre-Training Objective로 함. 19년도 논문이라 Old한 느낌이 있지만, Google Docs의 Auto-Generated Summaries에 실제 사용된 모델이고, Dialogue State Tracking (DST) Tasks에서도 좋은 성능을 보인다는 연구가 존재하는 등 활용도가 높아 보임.<br/><br/>
References:
* [PEGASUS](https://arxiv.org/abs/1912.08777)
* [Google Docs-Auto-Generated Summaries](https://ai.googleblog.com/2022/03/auto-generated-summaries-in-google-docs.html)
* [Effective Sequence-to-Sequence Dialogue State Tracking](https://arxiv.org/abs/2108.13990)

간단한 [Review](https://chainsmokers.oopy.io/diary/pegasus)
