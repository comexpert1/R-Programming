# R programming


R 및 R Studio 설치 

• R – CRAN (Comprehensive R Archive Network) – http://www.cran.r-project.org – Base System : R 프로그램 – Package : R 함수, 데이터, 컴파일된 코드를 모아 놓은 것

• R Studio – R을 쉽게 사용할 수 있는 IDE 소프트웨어 – 프로그램 입력, 관리, 그래픽, 패키지 윈도우 – https://www.rstudio.com/products/rstudio/download



R 사용자 인터페이스

• 워킹 디렉터리(Working Directory) – R에서 파일을 불러오거나 저장할 때 사용하는 디렉터리

• 함수와 객체 – 기본 내장 : vectors, matrices, data frames, lists, functions – 사용자 작성 : 함수 및 객체를 프로그래밍하여 사용

• 변수 – 하나의 속성을 가지고 다양한 값을 지님 – 데이터 분석의 대상 – 변수명 생성 규칙 • score, grade 등 알아보기 쉽고 기억하기 쉽게 작성 • 문자, 숫자, 대시(-), 언더바(_)를 조합 • 문자로 시작

• 데이터와 데이터셋(Dataset) – 데이터셋 : 여러 관측값을 가지는 것

• R 데이터 형태 (Mode) – 숫자형(Numeric) • 숫자로만 이루어진 것 – 문자형 (character) • “” 또는 ‘’로 표시 – 논리형 (logical value:True, False) • 내부적으로 True는 1 , False는 0 • 0 이외의 수는 True

• 데이터 형태 확인 is.numeric(), is.array(), is.character(), is.data.frame(), is.matrix()

