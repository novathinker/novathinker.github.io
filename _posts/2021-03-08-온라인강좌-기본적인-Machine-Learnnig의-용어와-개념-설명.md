---
layout: post
title:  "온라인강좌 기본적인 Machine Learnnig의 용어와 개념 설명"
author:  novathinker
tags: 머신러닝, 딥러닝
---


[![Video Label](http://img.youtube.com/vi/qPMeuL2LIqY/0.jpg)](https://youtu.be/qPMeuL2LIqY) 


1) 머신러닝은 무엇인가?
 - 정확한(명시적인) 프로그래밍의 한계
   - 너무 많은 룰들 (스팸필터, 자율주행)
 - 아서 사무엘 : 일일이 프로그램하지 말로 현상에서 배워 적용하자

2) 지도학습과 비지도학습
 - 지도학습 : 레이블이 붙어 있는 데이터로 학습
 - 비지도학습 : 일일히 레이블을 붙일 수 없는 데이터들을 대상
   - 뉴스그룹핑, 유사 단어끼리 모으기

3) 지도학습
 - 머신러닝에서 가장 일상적인 문제들
 - 이미지 레이블링 : 태깅된 데이터에서 학습
 - 이메일 스팸필터 : 레이블이 달린 이메일에서 학습
 - 시험 점수 예측 : 이전에 시험 준비 시간과 결과로 학습

4) 학습 데이터 셋(Training Data Set)
 - 레이블이 달린 데이터로 학습을 수행 
   --> 모델 생성
   --> 모델에 유사형태 데이터를 던지면 레이블의 값을 반환

5) 지도학습의 유형
 - 회귀(regession) : 공부 시간으로 시험 점수 예측
   
 - 이진 분류(binary classification) : 공부 시간으로 합격/불합격이라는 두 가지 값 중 하나를 찾는 것
 - 다중 라벨 분류 (multi-label classification) : 공부 시간으로 학점을 예측

 ?) 다중 라벨 분류는 multi-class분류와 대비하여 얘기가 되던데... 
    [관련 블로그](https://blog.naver.com/PostView.nhn?blogId=sw4r&logNo=221714823560&categoryNo=0&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=postView)를 참고하도록 하고 일단 넘어가자..
