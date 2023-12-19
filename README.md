## 주제: 스마트폰 출시 전후 관련 영상의 조회수 증가율의 차이 파악
사용 데이터 셋: https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset

### 데이터 설명
|Column|설명|
|--|--|
video_id         |비디오 ID
title            |제목
publishedAt      |업로드 날짜
channelId        |채널 ID
channelTitle     |채널명
categoryId       |카테고리 분류 ID
trending_date    |트렌딩에 올라간 날짜
tags             |태그
view_count       |조회 수
likes            |좋아요 수
dislikes         |싫어요 수
comment_count    |댓글 수
thumbnail_link   |썸네일 링크
comments_disabled|댓글 비활성화
ratings_disabled |평가 비활성화
description      |영상 설명

출시 전후 기준을 trending_date로 설정하여 분석을 진행했다.

### 스마트폰 출시 전후 영상의 조회수 증가율 파악
갤럭시 모델을 기준으로 전후 영상의 조회수 증가율 차이를 확인하였다. 

결과는 출시 전 영상의 조회수 증가율이 높은 것을 볼 수 있었다. 
![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/a9ebd444-1fd4-4b77-9880-a2c626d27d6b/41f5abb6-0b47-4e9d-94f1-dcb846ce423b/Untitled.png)




### 갤럭시 vs. 아이폰 모델별 조회수 증가율 그래프
유명한 두 브랜드에 대한 영상을 가지고 출시일 기준으로 조회수의 증가율을 계산한 결과입니다.

21년 모델
![21년모델](https://github.com/lasentia/YouTube-Trend-Analysis-Project/assets/128382645/7a55c353-90c3-4dce-b18d-0d53bb4bfac9)
22년 모델
![22년모델](https://github.com/lasentia/YouTube-Trend-Analysis-Project/assets/128382645/5e9854d9-3108-4f28-b92a-879294b1fa71)
23년 모델
![23년모델](https://github.com/lasentia/YouTube-Trend-Analysis-Project/assets/128382645/06eae53b-15be-423b-aae1-b397b8db95ed)


### 결론
스마트폰 관련 영상은 출시일 전에 업로드 하는 것이 더 높은 조회수 증가율의 성향을 띄는 것을 확인할 수 있었다.
따라서, 테크 유튜버로 영상을 제작을 한다면 출시 전 영상 제작이 더 높은 조회수와 수익을 가져다 줄 수 있다.

### 아쉬운 점
결과 내용을 정리하다보니 영상을 출시 전 후 제목으로 영상을 더 세분하게 필터링을 했다면 더 정확한 분석결과가 나왔을 것 같다.
출시일 기준으로 trending_date의 영상을 나눈 것이 같은 영상이라도 출시 전과 후의 차이를 파악할 수 있을 것이라 판단하였기 때문이다. 하지만 다시 생각하면 주제와 다른 방향이지 않았다 생각이 든다. 
