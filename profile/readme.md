<h2 align="center"> 💇‍♀️모락모락 (毛樂毛樂) - 맞춤형 헤어스타일 추천 서비스</h2>



_내 얼굴형에 맞는 헤어스타일을 추천 받고 싶다면?_ <br> 
👉 [모락모락 바로 가기👈](https://morak-morak-demo.vercel.app/)


### **👩 합성사진으로 헤어스타일 추천** <br>
: 사용자의 얼굴 이미지를 통해 얼굴형(하트형, 긴형, 계란형, 사각형, 둥근형)을 분석한 후, 분석된 얼굴형에 어울리는 헤어스타일을 합성한 사진 3장과 어울리지 않는 헤어스타일을 합성한 사진 3장을 가시적으로 보여주는 기능

### **✒️ 디자이너 추천** <br> 
: 위의 기능에서 추천된 헤어스타일을 기반으로, 해당 헤어스타일을 전문 헤어로 등록한 디자이너들을 리스트 형태로 제공하는 기능

### **👁️‍🗨️ 디자이너 포트폴리오 생성** <br>
: 디자이너가 자신의 정보, 근무지, 자격인증서, 전문헤어, 헤어 이미지, 가격 등을 넣어 자신만의 포트폴리오를 생성하는 기능



## 👥 팀원

<div align=center> 

  | 김지원(BACK) | 오예린(FRONT) | 황서정(AI) | 
  | :---: | :---: | :---: | 
  | <img src="https://avatars.githubusercontent.com/JiwonKim08" alt="profile" width="180" height="180"> | <img src="https://avatars.githubusercontent.com/YelynnOh" alt="profile"   width="180" height="180"> | <img src="https://avatars.githubusercontent.com/seojungH" alt="profile" width="180" height="180"> |
  | [JiwonKim08](https://github.com/JiwonKim08) | [YelynnOh](https://github.com/YelynnOh) | [seojungH](https://github.com/seojungH) | 

</div>

## ✨ 기술 스택

<div align=center> 
  <br>
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white">
  <br>
    <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  
    <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">

  <br>
</div>


## ❔ How to install, build, test ❔
- FRONT
    -
    - 
    -  
- BACK
    -
    - 
    -

- AI
    -
    - 
    -

<br>
cf. 서버간 연결동작은 로컬에서 불가능합니다.


## 💦 sample data 설명 (AI)

## 🛠 프로젝트 전체 구조도
![전체구조도](https://github.com/Algo-Artisans/.github/assets/99666136/f9dc4e53-de50-4f62-b50c-b87226e54f9b)

## 🎯 주요 코드 설명
- FRONT
    -
    - 
 
    ```

    ```
    -
    ```
    ```

- BACK
    -
    - QueryDSL을 사용해 '헤어디자이너 추천 기능' 구현
    ``` 
        for (String hairName : hairNames) {
            Long hairStyleId = queryFactory
                .select(QHairStyle.hairStyle.hairStyleId)
                .from(QHairStyle.hairStyle)
                .where(QHairStyle.hairStyle.hairName.eq(hairName))
                .fetchOne();

            if (hairStyleId != null) {
                List<Long> portfolioIdsForHairName = queryFactory
                    .selectDistinct(qportfolioHairStyle.portfolio.portfolioId)
                    .from(qportfolioHairStyle)
                    .where(qportfolioHairStyle.hairStyle.hairStyleId.eq(hairStyleId))
                    .fetch();

            portfolioIds.addAll(portfolioIdsForHairName);
            }
        }
     ```
- AI
    -
    - 
 
    ```

    ```
    -
    ```
    ```


## 🔗 기술 블로그 링크
- [백엔드 작업환경 세팅하기👈](https://jwkdevelop.tistory.com/131)
-
-
-

## 🔗 최종 보고서 링크
- pdf 파일 올리기
