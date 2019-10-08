# Text Classification Lecture Code

## Assignments
### Single Sentence Classification (Assignment 1)
1. Training with base model which includes base RNN with 5 epochs. (1 pt)
2. During (1.), report your train and valid accuracy for every epoch and report test accuracy. (1 pt)
3. Train using **advanced method** at least with multi-layer bidirectional LSTM with 5 epochs. (1 pt)
4. During (3.), report your train and valid accuracy for every epoch and report test accuracy. (1 pt)
5. Report the number of parameters in the two layered bidirectional LSTM. (1 pt)  

1, 2번 소과제에 대해서는 TextClassification_base.ipynb를 이용해서 주어진 base model로 Text Classification을 해보시고,
각 epoch의 Train, valid 결과와 최종 test 결과를 report 해주시면 됩니다.  

3, 4번 소과제에 대해서는 주어진 TextClassification_base.ipynb를 바탕으로, 강의 ppt(single_sentence_classification.pptx)의 Advanced model 파트를 참고하여 Base Model을 발전시키신 후에, 발전된 Model을 이용하여 진행한 Training에서의 각 epoch의 Train, valid 결과와 최종 test 결과를 report 해주시면 됩니다.  

5번 소과제에 대해서는 TextClassification_base.ipynb의 class RNN의 RNN을 two layered bi-direcional LSTM으로 바꾼 후 모델을 생성하고, 그 모델의 parameter 갯수를 측정하여 report 해주시면 됩니다. 만약 ppt의 advanced model 파트를 따라서 3, 4번 소과제를 완료하셨다면, 파일 내에 이미 정의된 함수를 이용해 쉽게 완료하실 수 있습니다.  

각 소과제에 대해서 주피터 노트북의 **출력 셀**을 캡쳐하셔서 word 문서에 작성 후 보내주시면 되겠습니다. 2,4 소과제를 하셔서 결과를 쓰셨다면 1,3 소과제에는 추가적으로 report 하실 것이 없으므로 공란으로 두셔도 됩니다. (단, 2 소과제를 수행하지 않으면 1 소과제도 0점처리 되며, 마찬가지로 4 소과제를 수행하지 않으면 3 소과제도 0점처리 됩니다.)  

**출력 셀**의 포맷은 single_sentence_classification.pptx의 45, 96, 97번 슬라이드를 참고하시면 됩니다.  

정리하자면 Assignment1을 위해서는 다음을 *zzxc1133@kaist.ac.kr*로 제출해주시면 됩니다.:  

1) 소과제 1,2,3,4,5에 해당하는 각 결과 (캡쳐한 출력 셀)을 작성한 Word 파일 (파일 확장자는 .docx 또는 .pdf) (**필수**)
2) **Advanced Model**을 반영한 TextClassification_base.ipynd (선택)  


더 자세한 정보는 현 repository의 single_sentence_classification.pptx를 참고하여 주시기 바랍니다.  

문의 사항 있으시면 zzxc1133@kaist.ac.kr로 보내주세요.  
