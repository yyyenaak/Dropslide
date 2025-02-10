# 🌟 호버 드롭다운 슬라이더 (Swiper.js)

## 🖥️ 프로젝트 소개
**"슬라이더를 더욱 직관적으로!"**
- Swiper.js를 활용하여 제작된 호버 시 드롭다운되는 반응형 슬라이더입니다.
- 데스크톱과 모바일 환경에서 부드러운 애니메이션과 내비게이션 컨트롤을 지원합니다.
- CSS와 JavaScript를 활용하여 커스터마이징이 용이한 구조로 개발되었습니다.

## 🕰️ 개발 기간
- 2024.04 - 2024.05

## ⚙️ 개발 환경
### <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/> <img src="https://img.shields.io/badge/Swiper.js-6332F6?style=flat-square&logo=swiper&logoColor=white"/>

---
## 📌 주요 기능
### 🔹 **호버 드롭다운 슬라이더**
- 사용자가 마우스를 올리면 슬라이더가 활성화되어 확대됩니다.
- `swiper-container` 클래스 내부에 `swiper-slide`를 구성하여 슬라이드를 추가할 수 있습니다.

### 🔹 **반응형 디자인 지원**
- 데스크톱과 모바일 환경을 고려하여 `@media` 쿼리를 활용한 스타일 적용
- 모바일에서는 네비게이션 버튼이 비활성화되고 터치 제스처로 조작 가능

### 🔹 **자동 재생 및 루프 기능**
- `autoplay` 기능을 활용하여 일정 간격으로 슬라이드 전환
- `loop: true` 옵션으로 무한 루프 설정 가능

---
## 📂 프로젝트 폴더 구조
```
project-folder/

│── index.html          # 메인 HTML 파일
│── swiperstyle.css     # Swiper css
│── style.css           # 슬라이드 css 
│── swipermin.js        # Swiper.js 라이브러리
│── img/                # 슬라이드 이미지 파일
│── README.md           # 문서 파일
```

## ⚙️ 커스터마이징 방법
### 🎛️ 자동 재생 속도 변경
```js
const options = {
    autoplay: {
      delay: 2500, // 원하는 속도(ms)로 변경
      disableOnInteraction: false,
    },
};
```

### 🎛️ 슬라이드 간격 조정
```
const options = {
    spaceBetween: 50, // 간격을 원하는 값으로 변경
};
```

## 🖼️ 스크린샷
![image](https://github.com/user-attachments/assets/fb287a8f-b929-427b-a1db-85839f7b9649)

