### 반응형 웹 프로젝트 

![스크린샷1](https://github.com/user-attachments/assets/3e82e29c-d41f-450d-bae4-634edef8ef82)
![스크린샷2](https://github.com/user-attachments/assets/c0216b85-cbd6-44e3-a5b2-46170e56449b)
![스크린샷 3](https://github.com/user-attachments/assets/9c61aa6d-2b2c-44cc-b793-7d8a59de61cf)


**개요**

풀스텍 웹 개발을 처음 시작하면서, 프론트엔드의 기본적인 개념을 익히고 싶었습니다. 특히 HTML,CSS,JavaScript를 활용하여 정적인 웹 페이지를 구현하며, 웹의 구조와 스타일링, 그리고 반응형 웹 디자인을 학습하는 것이 목표였습니다. 
이 과정에서 다양한 라이브러리들을 이용하여 반응형 디자인, 웹 표준, 크로스 브라우징 이슈 등을 경험하며 실무에서 필요한 핵심 개념을 익힐 수 있었습니다. 
 해당 기본기를 바탕으로, 클라이언트 사이드 렌더링(CSR) 측면에서는 React를 학습하며 이해할 것이며, 서버 사이드 렌더링(SSR) 측면에서는 스프링 타임리프(Thymeleaf) 같은 템플릿을 통해서 학습할 것입니다. 
 

**배포**

https://webpageminiproject.netlify.app/


- **기간**: 25일  (2024.08.03 ~ 2024.08.27)
- **팀 구성**: 1인 미니 프로젝트 
- **기술 스택**: HTML,CSS(Bootstrap 5),JavaScript 

**구현 기능**

- 시멘틱 웹 방식을 이용한 정적 홈페이지 구현
  강의 리스트 제공
  커리큘럼 정보
  서적 리스트 
- 반응형 웹 디자인 : 다양한 화면 크기에 최적화된 UI 구현 
- 미니 검색 엔진을 구현하여 전공/교양 과목을 검색하고 원하는 방식으로 정렬
- 파비콘 설정 : 다양한 환경에서 사이트 아이콘 표시 
- 소셜 미디어 메타 태그 설정 : Facebook, Twitter에서 미리보기가 최적화되도록 Open Graph 설정 


**특이사항**


- **문제 해결 및 의사결정 능력**

1️⃣ 메타 태그(Open Graph) 설정을 통한 SNS 미리보기 최적화

프로젝트를 GitHub Pages를 통해 배포하는 과정에서 링크 공유 시 썸네일과 설명이 표시되지 않는 문제 발생
Open Graph 및 Twitter Card 메타 태그를 추가하여 Facebook, Twitter에서 미리보기 화면이 정상적으로 표시되도록 해결  

2️⃣ 정적인 웹사이트를 최적화하여 반응형 웹 구현

다양한 기기(PC, 모바일)에서 UI가 깨지는 문제 발생
CSS @media 쿼리를 활용하여 반응형 디자인을 적용하여 모바일에서도 정상적으로 레이아웃이 유지되도록 개선

3️⃣ 파비콘(Favicon) 적용 과정에서 브라우저별 호환성 문제 해결

일부 브라우저(IE, Safari)에서 파비콘이 정상적으로 표시되지 않는 문제 발생
다양한 환경을 고려하여 .png 및 .ico 포맷을 각각 설정하고, link rel="icon" 및 rel="apple-touch-icon"을 추가하여 모든 환경에서 정상적으로 표시되도록 해결

4️⃣ 강의 리스트 및 서적 리스트의 UI 정리 및 사용자 경험(UX) 개선

학습 자료가 많아지면서 목록이 길어져 가독성이 떨어지는 문제 발생
CSS 애니메이션을 활용한 슬라이드 기능을 추가하고, 화살표 버튼을 이용한 네비게이션 기능을 적용하여 사용자 경험 개선

5️⃣ 크로스 브라우징 이슈 해결 

여러가지 브라우저 호환 문제 발생
바벨을 사용하여 자바스크립트 버전에 따른 호환 문제 해결, normalize.css를 사용하여 브라우저 스타일 차이 보정 
 
    
 **기술 학습 및 사후 관리 역량**

 정적 홈페이지를 만들어 봄으로서, 차후 제작할 동적 홈페이지에 대한 기초를 다졌다.
 클라이언트 사이드 렌더링(CSR) 측면에서는 React를 학습하며 이해할 것이며, 서버 사이드 렌더링(SSR) 측면에서는 스프링 타임리프(Thymeleaf) 같은 템플릿을 통해서 학습할 것입니다. 
 
    
    

**참고 링크**
- **Inflearn**: [풀스택을 위한 탄탄한 프런트엔드 부트캠프](https://www.inflearn.com/course/%EA%B0%95%EC%9D%98%ED%8F%89%EA%B0%80-%EC%82%AC%EC%9D%B4%ED%8A%B8-jsp/dashboard)
- **Nomalize**: [Nomalize CSS](https://necolas.github.io/normalize.css/)
- **Animate.css**: [Animate](https://animate.style/)
- **FontAwesome**: [FontAwesome](https://fontawesome.com/)

