[220708 회의록]

- 주제 선정
  - 오운완 - Lookmafit 



- 기능 분류

  - Account 

    - 로그인
      - 소셜네트워크 로그인
      - JWT 토큰 인증방식
    - 회원가입
      - 소셜네트워크 회원가입
        - 리다이렉트로 키, 몸무게, 관심 운동 기입할수 있게
        - 키 몸무게 관심운동 은 공개 / 비공개  할 수 있게
      - 키 , 무게, 관심 운동(적어도 한개는 선택하게)

    - 로그아웃
      - 로그아웃 버튼
    - 설정
      - 회원탈퇴
        - 설정 버튼안에 회원탈퇴 
        - 회원탈퇴시 비밀번호 확인 
        - 탈퇴해도 실제 DB에서 삭제 
          - 해당 회원과 관련된 댓글 게시글 대댓글 다삭제
      - 회원정보 변경
        - 설정 버튼안에 회원변경
        - 비밀번호 변경
    - 마이페이지
      - 키, 몸무게 수정 가능하게
      - 키 ,몸무게을 통해 ( BMI ) 변화 볼수있게 그래프 또는 시각적인 요소로 보고싶다 
      - 그래프 ( 운동 능력치 )
      - 잔디 ( 꾸준히 한다는 것을 )
        - 덤벨 모양
      - 팔로우 / 팔로잉
        - 인스타랑 비슷하게 
        - 뉴스 피드에 상위에 뜨게 구현
      - 쪽지

    Community

    - 게시글 쓰기

      - 제목
      - 카테고리
        - 몸 (어깨, 등) 같이 운동했던 근육들을 적을 수 있게
        - 자동완성 기능 ( 해시태그한 것은 자동완성 되게 )
        - 여러개 선택 가능
      - 글 종류 선택
        - 비밀글 ( 자신만 )
        - 비밀글 ( 자신과 팔로우 )
        - 공개글 
      - 본문

      - 자기 운동 영상
        - 파일첨부 -> 영상 띄우기 

    - 게시글 조회

      - 게시글 오른쪽 상단에  신고버튼 활성화
      - 게시글 공유 & 링크 버튼
      - 비밀 글
        - 자신만 볼 수 있는 글
        - 자신과 팔로우 한 사람만 볼 수 있는 글
        - 모두가 볼 수 있는 글
      - 좋아요 버튼

    - 게시글 수정

      - 작성자만 가능하게
      - 본문만 수정 가능하게
      - 악용이 될 가능성이 있기에

    - 게시글 삭제

      - 작성자만 가능하게
      - 경고창

    - 게시글 추천

      - 비슷한 키와 몸무게를 가진 사람들의 변화된 모습 보여주기
      - 추천 시스템

    - 댓글 조회

      - 상세 게시글에서 볼 수 있게
      - 본문
      - 좋아요 기능

    - 댓글 수정

      - 수정 X
      - 악용이 될 가능성 

    - 댓글 삭제

      - 게시글 작성자가 댓글 삭제가능

    - 댓글 쓰기

      - 로그인 한 사람만
      - 게시글 작성자에게 알람기능

    - 대댓글 도 가능하게

      - 댓글 작성자에 알람기능 

    - 좋아요 버튼 

      - 댓글 작성자에게 알람기능

  - 알람

    - 네비게이션 바 에 보이게



- 추가적인 기능(후순위)
  - 휴면계정
  - 캐릭터
    - 그래프로 캐릭터 성장
    - 운동에 따라 팔 다리가 다르게 성장
      - 업적 달성  -> 프로필 변경
    - 알에서 부터 점점 커지게
      - 동물농장
  - 근육별로 카테고리
  - 게시글 댓글 차단 기능



- 7월 11일(월요일)까지 할 일
  - Back-end: ERD / REST API 구조 설계
    - 만들고 피드백

  - Front-end: UI / UX 기획
    - 피그마 제작
      - 회원가입 / 로그인 쪽 ( 김가흔 )
      - 마이페이지  ( 장창완 )
      - 메인페이지 ( 이동근 )
      - 상세 글  /  게시글 생성  ( 최지은 )

    - 컴포넌트 설계
      - 각자 페이지 컴포넌트 설계


