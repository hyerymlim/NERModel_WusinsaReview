# 우신사 리뷰 댓글 개체명 인식 모델
# NER Model For Wusinsa Review
이 프로젝트는 K-Digital 빅데이터 과정 수강생 7명이 공동으로 작업한 프로젝트입니다.

프로젝트 수행과정에 대한 더욱 세부적인 사항은 .ipynb 파일에서 확인하실 수 있습니다.

## 팀원 소개
>김준기 star956733@gmail.com
>
>엄성현 tjdgus510@gmail.com
>
>이경진 kungjin0119@naver.com
>
>이상화 templas332@naver.com
>
>임혜림 eim0801@naver.com
>
>조민지 study.minji.study@gmail.com
>
>하은겸 foreverek4th@naver.com

![image](https://user-images.githubusercontent.com/92901802/157468547-71ca060d-32b6-4387-be8c-26c518b3eb09.png)

![image](https://user-images.githubusercontent.com/92901802/157468627-9350443d-665e-4f72-835e-f35578f53fd3.png)

![image](https://user-images.githubusercontent.com/92901802/157468692-660cb119-7944-4f3f-b720-6a4c9da8c788.png)

![image](https://user-images.githubusercontent.com/92901802/157468752-c39a8ce8-e60a-4a7c-b20b-0a1539e4d59b.png)

![image](https://user-images.githubusercontent.com/92901802/157468925-e4f73a2f-e8e5-44aa-86be-04f252d7ad84.png)

![image](https://user-images.githubusercontent.com/92901802/157468981-73dfe438-1952-4c1d-a6de-803aec4f0a5f.png)

![image](https://user-images.githubusercontent.com/92901802/157469020-5b13dd0f-6e54-4515-9ecd-1c338ae652e1.png)

![image](https://user-images.githubusercontent.com/92901802/157469245-8676fc0a-5b8e-49c4-b3c8-5b60ddfc9211.png)

![image](https://user-images.githubusercontent.com/92901802/157469293-9b96a347-7b09-4462-98a7-6950c0776c0b.png)

![image](https://user-images.githubusercontent.com/92901802/157469330-f99b3ee9-00f1-49a7-9e84-e4c3fc6a7d35.png)

![image](https://user-images.githubusercontent.com/92901802/157469365-84c0c42c-6bbd-4c7c-8989-b9545e3d157a.png)

![image](https://user-images.githubusercontent.com/92901802/157469404-9ca144ff-9ba9-4343-bfaa-814f7a6783d9.png)

![image](https://user-images.githubusercontent.com/92901802/157469434-294127a3-e0ef-4824-b09d-1deb6fde8aca.png)

![image](https://user-images.githubusercontent.com/92901802/157469536-d2312d2a-9db7-4c01-b38a-2c5d7bc3aab1.png)

![image](https://user-images.githubusercontent.com/92901802/157469592-8eb5715e-d2d1-43fd-bc71-267c6c20fe0e.png)

![image](https://user-images.githubusercontent.com/92901802/157469644-c43a1c5b-5890-412d-9add-d45ce5b2ea83.png)

![image](https://user-images.githubusercontent.com/92901802/157469826-7b979989-0d0d-4524-9d69-29f1acfa6447.png)

![image](https://user-images.githubusercontent.com/92901802/157469899-308cbfbd-f7c1-4ec3-8046-53f5c79b31e4.png)

![image](https://user-images.githubusercontent.com/92901802/157469938-423ff117-98c7-41d4-8e5b-c4352788db41.png)

![image](https://user-images.githubusercontent.com/92901802/157470007-cd8290c1-6a9f-4509-8140-4fa40debd2b7.png)

![image](https://user-images.githubusercontent.com/92901802/157470060-0ebedacf-e769-4077-985d-055ff7650701.png)

![image](https://user-images.githubusercontent.com/92901802/157470118-56caac8c-3b8c-4870-935d-0a3911e2b154.png)

![image](https://user-images.githubusercontent.com/92901802/157470175-20c140b9-217f-4317-aa09-e3fbe6219348.png)

![image](https://user-images.githubusercontent.com/92901802/157470217-24ee1405-a1d3-43f8-ad58-479d3a44560b.png)

### 개선 방향 내용 추가(2022. 01. 10.)
사람이 직접 모든 문장에 태깅을 하는 작업은 데이터 확보나 태그의 일관성 확보에 있어서 상당히 비효율적이었습니다.

이는 확보할 수 있는 데이터의 절대적인 수를 현저히 감소시켰으며, 사람의 주관이 주입된 태깅은 모델의 정확도가 더 이상 높아지지 못하도록 제한하였습니다.

이에 따라 k평균과 같은 군집화(Clustering) 알고리즘을 적용하는 방안을 추후 모색하고자 합니다.

비지도학습으로 모델링한다면, 태깅 작업에 따른 한계로 발생하는 문제들을 대거 해결할 수 있을 것으로 기대하고 있습니다.








