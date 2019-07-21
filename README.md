# Medical_Deeplearning

#### 이 소스코드는 의료영상처리 딥러닝을 위한 소스코드입니다.

## Gihub 란?
* **프로그램 등의 소스 코드 관리를 위한 분산 버전 관리 시스템이다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/35986429/61581865-ffe53e00-ab5e-11e9-88f1-7b8e0f29fbb7.JPG" width="800" height="350">
</p>

환경설정
ex)
git config --global user.name 계정이름
git config --global user.email 깃허브 이메일

다운로드
ex) git clone 깃허브 url

git add : 파일을 프로젝트에 추가.
ex) git add 파일이름

git commit : 파일이 올라간 시점을 스냅샷으로 찍음.
ex) git commit -m "변경 내용 log"

git push : 원격 저장소(git hub)에 파일을 적용.
ex) git push

git fetch : 원격 저장소(git hub)에 올려진 파일을 내 컴퓨터에 다운로드.
ex) git fetch

git merge : 특정한 파일에서 다른 사람이 작성한 코드와 내 컴퓨터의 코드를 맞춤.
ex) git merge

git pull : git fetch + git merge
ex) git pull

## Google Colab 이란?

[Tutorial 실습 링크](https://colab.research.google.com/github/Yonsei-MILab/Medical_Deeplearning/blob/master/CNN_VGG(Cifar10).ipynb)

## CPU와 GPU 란?

<p align="center">
  <img src="https://user-images.githubusercontent.com/35986429/61581719-c3184780-ab5c-11e9-8d98-ffaa6e526e01.JPG" width="700" height="300">
</p>

* CPU : 내부 면적의 절반 이상은 캐시 메모리로 채워져 있다. 캐시 메모리는 CPU와 램(RAM)과의 속도차이로 발행하는 병목현상을 막기 위한 장치다. CPU가 처리할 데이터를 미리 RAM에서 불러와 CPU 내부 캐시 메모리에 임시로 저장해 처리 속도를 높일 수 있다.

* GPU :  여러 명령어를 동시에 처리하는 병렬 처리 방식을 가지고 있다. 캐시 메모리 비중이 크지 않고 연산을 할 수 있는 ALU 개수가 많다.


Reference
https://www.youtube.com/watch?v=66c9QBXM2Fs&list=PLRx0vPvlEmdD5FLIdwTM4mKBgyjv4no81&index=4
