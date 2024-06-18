<h2 align="center"> 💇‍♀️모락모락 (毛樂毛樂) - 맞춤형 헤어스타일 추천 서비스</h2>



_내 얼굴형에 맞는 헤어스타일을 추천 받고 싶다면?_ <br> 
👉 [모락모락 바로 가기](https://morak-morak-demo.vercel.app/)


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
  <h3>FE</h3>
  <img src="https://img.shields.io/badge/Next.js-eeeeee?style=for-the-badge&logo=Next.js&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCss-06B6D4?style=for-the-badge&logo=TailwindCss&logoColor=white"/>
  <img src="https://img.shields.io/badge/ReactQuery-FF4154?style=for-the-badge&logo=ReactQuery&logoColor=white"/>
  <img alt="Yarn" src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white" />
  <img alt="Yarn" src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />


  <h3>BE</h3>
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  

  <h3>AI</h3>
  <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white">


  <h3>공통</h3>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">

  <br>
</div>


## ❔ How to install, build, test ❔
- FRONT
    - front 레포지토리의 코드를 로컬 환경으로 pull한다.
    - 프로젝트 폴더 가장 상위 폴더에 `.env.local` 파일 생성 후 필요한 환경 변수를 입력한다. 
    -  VScode의 터미널을 열어 `yarn` 명령어로 필요한 의존성을 설치한다. 
    - `yarn dev` 명령어로 Next.js 개발 서버를 띄운 후, `http://localhost:3000`을 진입 시 개발 화면을 확인할 수 있다. 
- BACK
    - 
    - back 레포지토리에서 최신코드를 IntelliJ로 pull한 뒤, `application.yml` 파일에 설정값을 입력한다.
    - 오른쪽 상단에 Run 버튼을 눌러 localhost 서버를 띄어 터미널에 뜬 주소로 들어간다.
    - 프론트와 연결되기 전이므로(배포주소가 아닌 localhost이므로), `http://localhost:8080/swagger-ui/`에서 API 테스트가 가능하다.
    - 단, 토큰 발급 전이므로(배포주소가 아닌 localhost이므로), 토큰이 필요한 API는 테스트 불가능하다.

- AI
    -
    - 
    -

<br>
cf. 서버간 연결동작(FRONT-BACK-AI)은 localhost에서 불가능합니다.


## 💦 sample data 설명 (AI)

<img src="https://github.com/Algo-Artisans/.github/assets/99666136/529ab123-da07-4282-8c8c-56da8dca519b" alt="합성 결과" width="400" height="600">


## 🛠 프로젝트 전체 구조도
![전체구조도](https://github.com/Algo-Artisans/.github/assets/99666136/f9dc4e53-de50-4f62-b50c-b87226e54f9b)

## 🎯 주요 코드 설명
- 코드 설명은 추석처리 해두었습니다.
- FRONT
    -
    - Next.js의 middleware 활용 코드
        - 사용자 인증 및 리다이렉트용으로 구성
    
    ```typescript
    import { NextResponse } from 'next/server';
    import type { NextRequest } from 'next/server';

    export async function middleware(request: NextRequest) {
    //NOTE : 카카오톡에서 토큰 받으면 그 토큰 쿠키에 저장
    if (request.nextUrl.pathname === '/auth') {
    //NOTE : url에서 토큰 부분 분리, 쿠키에 저장
    const accessToken = request.nextUrl.searchParams.get('accessToken');

    // NOTE : 이미 가입한 사람일 경우 홈 화면으로 이동 아니면 회원가입으로
    const firstLogin = request.nextUrl.searchParams.get('firstLogin');

    const response =
      firstLogin === 'no'
        ? NextResponse.redirect(new URL('/designerList', request.nextUrl))
        : NextResponse.redirect(new URL('/signup', request.nextUrl));

    if (accessToken) {
      response.cookies.set('accessToken', accessToken, { path: '/' });
    } else {
      // NOTE : 액세스 토큰이 없는 경우 요청을 거부하고 로그인 페이지로 리다이렉트
        return NextResponse.redirect(new URL('/login', request.nextUrl));
    }   

        return response;
        }
    }

    export const config = {
        matcher: ['/', '/auth'],
    };

    ```
    - S3 버킷에 저장되어 있는 '유저별 AI합성 이미지' 객체 직접 가져오기
        - 우선 아래와 같은 패키지가 필요함
        ```json
        "@aws-sdk/client-s3": "3.540.0",
        "@aws-sdk/credential-provider-node": "^3.554.0",
        ```
    ```typescript
    //useGetS3Image.ts
    const getS3Image = async (objectKeys: string[]): Promise<S3ImageProps> => {
    try {
        const s3Client = new S3Client({
        region: process.env.NEXT_PUBLIC_S3_REGION,
        credentials: {
            accessKeyId: process.env.NEXT_PUBLIC_KEY_ID || '',
            secretAccessKey: process.env.NEXT_PUBLIC_SECRET_ACCESS_KEY || '',
        },
        });

        const images = await Promise.all(
        objectKeys.map(async (objectKey) => {
            const command = new GetObjectCommand({
            Bucket: process.env.NEXT_PUBLIC_S3_BUCKET_NAME,
            Key: objectKey,
            });
            const response = await s3Client.send(command);

            if (response.Body) {
            const str = await response.Body.transformToByteArray();
            const blob = new Blob([str], { type: 'image/png' });
            return URL.createObjectURL(blob);
            }
            return ''; // 이미지가 없는 경우 빈 문자열 반환
        }),
        );

        // 이미지 URL 배열 반환
        return { urls: images.filter((url) => url !== '') };
    } catch (error) {
        console.error('S3 이미지 가져오기 실패:', error);
        throw error;
    }
    };
    ```

- BACK
    -
    - QueryDSL을 사용해 '헤어디자이너 추천 기능' 구현
    ```java
    public List<Portfolio> searchHairNames(List<String> hairNames) {
        QPortfolio portfolio = QPortfolio.portfolio;
        QPortfolioHairStyle qportfolioHairStyle = QPortfolioHairStyle.portfolioHairStyle;

        Set<Long> portfolioIds = new HashSet<>();
    
        // 리스트 hairNames에서 hairname을 꺼내 Id 가져오기
        for (String hairName : hairNames) {
            Long hairStyleId = queryFactory
                    .select(QHairStyle.hairStyle.hairStyleId)
                    .from(QHairStyle.hairStyle)
                    .where(QHairStyle.hairStyle.hairName.eq(hairName))
                    .fetchOne();

            // hairStyledId에 대응되는 portfolioId 가져오기
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
    
     - '디자이너 포트폴리오 등록 기능' 구현
     ```java
     public PortfolioResDto createPortfolio(HttpServletRequest httpRequest, PortfolioReqDto portfolioReqDto) {
        // 클라이언트 정보를 토큰에서 추출
        User user = jwtTokenProvider.getUserInfoByToken(httpRequest);

        // 디자이너인 경우에만 포트폴리오 생성 (접근제어)
        if (user.isDesigner()) {
            // 포트폴리오 생성
            Portfolio portfolio = Portfolio.builder()
                    .user(user)
                    .name(portfolioReqDto.getName())
                    .phoneNumber(portfolioReqDto.getPhoneNumber())
                    .workplace(portfolioReqDto.getWorkplace())
                    .snsAddress(portfolioReqDto.getSnsAddress())
                    .introduction(portfolioReqDto.getIntroduction())
                    .likesCount(0)
                    .styling1(portfolioReqDto.getStyling1())
                    .cost1(portfolioReqDto.getCost1())
                    .styling2(portfolioReqDto.getStyling2())
                    .cost2(portfolioReqDto.getCost2())
                    .styling3(portfolioReqDto.getStyling3())
                    .cost3(portfolioReqDto.getCost3())
                    .styling4(portfolioReqDto.getStyling4())
                    .cost4(portfolioReqDto.getCost4())
                    .profileURL(portfolioReqDto.getProfileURL())
                    .certificateURL(portfolioReqDto.getCertificateURL())
                    .imageUrl1(portfolioReqDto.getImageUrl1())
                    .imageUrl2(portfolioReqDto.getImageUrl2())
                    .imageUrl3(portfolioReqDto.getImageUrl3())
                    .imageUrl4(portfolioReqDto.getImageUrl4())
                    .isAdvertise(0)
                    .build();



            // PortfolioHairStyles 저장
            List<PortfolioHairStyle> portfolioHairStyles = new ArrayList<>();

            // HairName1에 해당하는 HairStyle 찾기
            HairStyle hairStyle1 = hairStyleRepository.findByHairName(portfolioReqDto.getHairName1());
            if (hairStyle1 != null) {
                PortfolioHairStyle portfolioHairStyle1 = PortfolioHairStyle.builder()
                        .portfolio(portfolio)
                        .hairStyle(hairStyle1)
                        .build();
                portfolioHairStyles.add(portfolioHairStyle1);
            }


            HairStyle hairStyle2 = hairStyleRepository.findByHairName(portfolioReqDto.getHairName2());;
            if (hairStyle2 != null) {
                PortfolioHairStyle portfolioHairStyle2 = PortfolioHairStyle.builder()
                        .portfolio(portfolio)
                        .hairStyle(hairStyle2)
                        .build();
                portfolioHairStyles.add(portfolioHairStyle2);
            }


            // HairName3에 해당하는 HairStyle 찾기
            HairStyle hairStyle3 = hairStyleRepository.findByHairName(portfolioReqDto.getHairName3());;
            if (hairStyle3 != null) {
                PortfolioHairStyle portfolioHairStyle3 = PortfolioHairStyle.builder()
                        .portfolio(portfolio)
                        .hairStyle(hairStyle3)
                        .build();
                portfolioHairStyles.add(portfolioHairStyle3);
            }


            // PortfolioHairStyles 저장
            portfolioHairStyles.forEach(portfolioHairStyleRepository::save);


            // Portfolio 저장
            portfolioRepository.save(portfolio);

        } else {
            throw new RuntimeException("디자이너가 아닌 사용자는 포트폴리오를 생성할 수 없습니다.");
        }
    }                
     ```
     
     - 카카오 로그인 인증 과정 구현 using Spring Security + 카카오 디벨로퍼
     ```java
     @Override
    public void onAuthenticationSuccess(HttpServletRequest request, HttpServletResponse response, Authentication authentication)
            throws IOException, ServletException {
        OAuth2User oAuth2User = (OAuth2User) authentication.getPrincipal(); // 카카오로부터 받은 유저 정보
        User user = userRepository.findUserByKakaoId(oAuth2User.getAttribute("id"))
                .orElseThrow(() -> new UsernameNotFoundException("회원이 존재하지 않습니다.")); // 해당 Id를 DB에서 조회
        String firstLogin = (user != null) ? "no" : "yes";
        String role = String.valueOf(user.getRole());

        String accessToken = jwtTokenProvider.createAccessToken(oAuth2User.getAttribute("id").toString(), role); //토큰발행
        String refreshToken = jwtTokenProvider.createRefreshToken(oAuth2User.getAttribute("id").toString(), role); //토큰발행
    
        String newtargetUrl;
        String referer = request.getHeader("Referer");
        if (referer.startsWith("http://localhost:3000/")) {
            newtargetUrl = UriComponentsBuilder.fromUriString("http://localhost:3000/auth")
                    .queryParam("accessToken", accessToken)
                    .queryParam("firstLogin", firstLogin)
                    .build().toUriString();
        } else {
            newtargetUrl = UriComponentsBuilder.fromUriString("https://morak-morak-demo.vercel.app/auth")
                    .queryParam("accessToken", accessToken)
                    .queryParam("firstLogin", firstLogin)
                    .build().toUriString();
        }
        getRedirectStrategy().sendRedirect(request, response, newtargetUrl);
    }
     ```

## 🔗 기술 블로그 링크
- 👉[백엔드 작업환경 세팅하기](https://jwkdevelop.tistory.com/131)
- 👉[프론트엔드 프로젝트 스캐폴딩 과정](https://shingy.tistory.com/56)
- 👉
- 👉

## 🔗 최종 보고서 링크
- 👉 [최종 피피티 및 보고서](https://jwkdevelop.tistory.com/133)
