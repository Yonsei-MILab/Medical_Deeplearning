# Medical Machine Learning

**This is a class exercise for Medical Machine Learning in Yonsei University**

## Google Colab 이란?

* #### Jupyter Notebook에서 활용하는 문서들을 하나의 공동작업의 문서로 통합해 주는 머신러닝 교육 데이터 분석 도구
     Google Drive + Jupyter Notebook(GPU 최대 사용시간 : 12시간)

## Github - Colab - Google Drive 연동
1. **https://colab.research.google.com 에 접속**

2. **Github 클릭 - 'Yonsei-MILab' 검색**
<p align="center">
  <img src="https://blogfiles.pstatic.net/MjAxOTA5MTFfMjIw/MDAxNTY4MTY0MTM4NTAw.PYQYzzwbdRckXR41if9XfG4UI_-MFoECAedXX9Z-zFAg.7s06tOptnO9-QV8aGq98RSDV9vUTPqbbUEduSXfBU3cg.PNG.susie1513/colab1.PNG" width="600" height="400">
</p>

3. **source code 복사 버튼 클릭** <img src="https://blogfiles.pstatic.net/MjAxOTA5MTFfMTIy/MDAxNTY4MTY0Mjg1ODU0.VuUeMEIhtiLsAdoyQX47BoN_Gm3mDydp5Euh96D1Rzsg.i_ZoOpsqP4pyti7vkG6vbXp6IEvtce-VZhQkTULS_Vsg.PNG.susie1513/colab2.PNG" width="20" height="20">

4. **파일-드라이브에 사본 저장 클릭**

<p align="center">
  <img src="https://blogfiles.pstatic.net/MjAxOTA5MTFfMjA4/MDAxNTY4MTY0NjA3NjUy.gyN2U6j27sTWfRM91X-spQJdXGGsuIPqk9hQNuBlFtsg.bOIM7Fjoz5cVVO0Y1YIpRtdcgfaRHS5QdXf6vzZIiYkg.PNG.susie1513/colab3.PNG" width="300" height="500">
</p>

5. **내 드라이브에 사본 파일 생성 확인**

<p align="center">
  <img src="https://blogfiles.pstatic.net/MjAxOTA5MTFfNjUg/MDAxNTY4MTY0ODQ2OTAy.o4LdUtco8rC0wGz8UB2RmjlGrwY4y4RUd539PmYwjGog.pza59EtrBiWH5FqCqE3z5K76XZJu8ET1YO7r_ldhFXog.PNG.susie1513/colab4.PNG" width="800" height="35">
</p>

6. **생성된 파일 우클릭 - 연결앱 - Google Colaboratory 클릭**

<p align="center">
  <img src="https://blogfiles.pstatic.net/MjAxOTA5MTFfMTU2/MDAxNTY4MTY0OTg4NTIz.mU3nE2-mRv67ndktmLFAVnsExHjq9fbHpZ3iNtpB_DMg.gsFTphAV8VdJJqg2_feoC9zvkJP2NuXMl334P8cw7Rgg.PNG.susie1513/colab5.PNG" width="430" height="300">
</p>

## Colab 환경 설정

1. **런타임 - 런타임 유형 변경 - GPU 로 변경**

<p align="center">
  <img src="https://blogfiles.pstatic.net/MjAxOTA5MTFfMTMx/MDAxNTY4MTY1NjI0MDEx.IBb0Q_h4IKwlNC4np_1ffg_9DsJgKE8CP_zkFSGU0LQg.NkHdyA0nJEe0WWr-_orhZvkEU6OQua2jnpzyQLhyEJ8g.PNG.susie1513/colab6.PNG" width="750" height="350">
</p>

2. **드라이브 마운트**

<p align="center">
  <img src="https://blogfiles.pstatic.net/MjAxOTA5MTFfNDYg/MDAxNTY4MTY2MTI4NTQz.MA1BDC12dckVeMRd3ZMF6yW93NagKNBEi-1pxyP4Zs4g.CfdM5eXHX9VSWsoxlMmXykJ0fr2UJNEPpqoBFnXjKXog.PNG.susie1513/colab7.PNG" width="600" height="300">
</p>

## CPU와 GPU 란?

<p align="center">
  <img src="https://user-images.githubusercontent.com/35986429/61581719-c3184780-ab5c-11e9-8d98-ffaa6e526e01.JPG" width="700" height="300">
</p>

* #### CPU  
내부 면적의 절반 이상은 캐시 메모리로 채워져 있다. 캐시 메모리는 CPU와 램(RAM)과의 속도차이로 발행하는 병목현상을 막기 위한 장치다. CPU가 처리할 데이터를 미리 RAM에서 불러와 CPU 내부 캐시 메모리에 임시로 저장해 처리 속도를 높일 수 있다.

* #### GPU  
여러 명령어를 동시에 처리하는 병렬 처리 방식을 가지고 있다. 캐시 메모리 비중이 크지 않고 연산을 할 수 있는 ALU 개수가 많다.

## 목차
#### 1. MNIST
#### 2. R2* mapping using MLP
