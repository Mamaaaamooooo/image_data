# image_data
이미지 데이터


MS COCO Captions 데이터셋의 영문 Caption 을 한국어 문장으로 번역. MS COCO 데이터셋 중 약 12만장에 해당하는 이미지의 설명문을 번역하였다. __※ [MS COCO 데이터셋 참고 (클릭)](https://cocodataset.org/#home)__

<br><br><br><br>
__※   [aihub 공식사이트(클릭)](https://dancetrack.github.io/) 에서 직접 다운로드 받을 수 있음.__


### 데이터 이미지
![이미지](https://github.com/Mamaaaamooooo/minsukeum/blob/main/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202024-06-27%20180258.png?raw=true)

### 데이터 사이즈 
| 내용  | 개수 | 
|:---:|:---:|
|train| 약 12만 개 | 


### 데이터 구조
| key값 | 형식 | 비고 | 
| :---: | :---: |:---: |
| file_path | str | 이미지 파일 경로  |
| id | int | 이미지의 id  |
| captions | list[str] | 이미지에 대한 설명(영문) |
| caption_ko | list[str] | 이미지에 대한 설명(한국어) |
