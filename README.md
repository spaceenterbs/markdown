1. 태초에 Markup이 있었다.
	Markdown은 텍스트 기반의 경량 마크업 언어 중 하나이다.
- 특별히 새로운 방식은 아니고 우리가 아는 HTML처럼 마크업 태그(기호)를 사용해 문서의 구조를 작성하는 언어이다.
= 마크다운은 아주 경량이며, 텍스트 편집기만으로도 구조화된 문서를 쉽고 빠르게 작성하는 것을 목표로 한다.
-- 무엇보다도 별도의 뷰어 없이 문서의 내용을 충분히 읽을 수 있는 장점이 있다.

- 마크업 언어의 대표인 HTML이 1980년까지 역사가 거슬러 올라가고 학술 문서의 공유를 위한 목적이 컸다면, 마크다운은 2004년 존 그루버라는 개인이 고안한 것이다.
= 이유는 간단했다. 웹 표준 마크업 언어인 HTML이 태그쌍을 중첩하는 복잡한 문서 구조 때문에 전용 에디터 없이는 작성이 쉽지 않고, 별도의 뷰어가 있어야 문서의 내용을 파악할 수 있는 것이 불편했기 때문이었다.
-- 텍스트 편집기만으로 전체 문서 작성이 가능해야 하고, 전용 뷰어 없이도 내용을 충분히 파악할 수 있는 마크업 언어를 목표로 만든 것이었다.
== 이름은 마크업의 반대인 마크다운으로 지었고 이는 비교적 최근에 인기를 끌기 시작했다.

6pg. 개발자라면 당연히 들락거리게 되는 깃허브에서 마크다운 포맷을 기본으로 지원하면서 개발자들의 사용이 급격히 늘었다.
- 문서의 구조가 조금만 복잡해지면 위지윅(WYSIWYG: What You See Is What You Get; 인쇄된 문서, 웹페이지, 슬라이드 PPT 등 완성된 결과물로서 인쇄 또는 표시될 때의 모습과 닮은 형태로 콘텐츠의 편집이 가능한 시스템) 에디터와 마우스가 필수인 HTML 문서와 달리, 텍스트 편집기와 키보드만으로 모든 문서의 구조를 빠르게 생성할 수 있기 때문에 문서 작업의 효율성이 높다.

------------------------------------------------------------------
7pg. 2. 마크다운 파일 확장자 .md
	깃허브 사이트나 인터넷에서 오픈소스 패키지나 압축파일을 다운로드 받았을 때 패키지 안에 "README.md" 파일이 패키지 루트에 포함되어 있는 것을 자주 볼 수 있다.
- 소스코드 배포의 기본 규칙처럼 정착된 사용법으로, 패키지를 배포하거나 소스 배포를 할 때 루트에 "README.md" 파일(또는 readme.html, readme.txt)로 코드에 대한 기록을 남기는 것이 표준 방식이 되었다.
= 마크다운 파일은 일반 텍스트 문서이다. 텍스트 편집기에서 열어볼 수 있고, 마크업 태그가 붙어있지만 마크다운 전용 뷰어가 아닌 메모장과 같은 일반 텍스트 편집기에서 열어 문서의 내용을 파악할 수 있다.
-- 소스코드와 같이 배포하는 마크다운 문서에는 버전 관리 히스토리, 설치 방법, 사용상 주의점, 오픈소스 관련 라이선스 정보 등 개발자가 알리려고 하는 기본적인 정보들을 담고 있다.