>강서구 랜드마크 추천을 위한 정보 크롤링 

## 구글 추천 활동 크롤링

<br>

|데이터|설명|
|:--:|:--:|
|place_name|관광지 이름|
|img_url|관광지 사진 링크|
|score|리뷰에 의한 별점|
|description|리뷰 갯수|

<br>
bs4를 사용하여 웹 파싱 후 정보 가져오기<br>
가져온 정보에서 정규 표현식을 이용하여 원하는 데이터 추출<br>
추출한 데이터를 웹에서 띄우기 위하여 json파일로 변환

<br>

___

<br>

JSON으로 추출한 데이터<br>

<img width="800" alt="Screen Shot 2022-06-10 at 3 00 12 PM" src="https://user-images.githubusercontent.com/80025122/173186114-cf41d67b-4d75-4003-97cb-1328294de36e.png">


데이터 프레임으로 추출한 데이터<br>

<img width="800" alt="Screen Shot 2022-06-10 at 3 00 47 PM" src="https://user-images.githubusercontent.com/80025122/173186110-2055b4d5-0d4a-4f42-b2c7-fef32d8b638c.png">

