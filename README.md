# Project_first

첫 번째 팀 프로젝트의 버전관리를 위한 저장소

[프로젝트 내용]

<데이터>

[응답결과][요청url?key=mongodb&query=sist][요청브라우저종류][일자 시간] 
응답결과 : 200-성공,404-페이지없음, 403-권한없음,
 500-서버내부오류

- 정량적분석(수치중심) :  어떤 대상이 얼마나 들어있는가?
- 정성적분석(대상중심) : 어떤 대상이 들어있는가?

<요구사항>
 주) SIST에서 운영하는 사이트인 http://sist.co.kr의 관리자인 당신은 사용자들의 검색정보가 log에 쌓이는 것을 인지하고, 이 log 파일에서 원하는 정보를 얻기 위한 프로그램을 개발하기로 한다. 

<필요한 정보>
1. 최다사용 키의 이름과 횟수  |  java xx회
2. 브라우저별 접속횟수, 비율
	IE - xx (xx%)
	Chrome - xx (xx%)

3. 서비스를 성공적으로 수행한 횟수, 실패(404) 횟수

4. 요청이 가장 많은 시간 [ 10 시]

5. 비정상적인 요청(403)이 발생한 횟수, 비율 구하기

6. 입력되는 라인에 해당하는 정보출력(1000~1500번째 라인에 해당하는 정보 중 최다사용 키의 이름과 횟수  |  java/ xx회)

7. view버튼과 report 생성버튼을 만들고 view버튼이 클릭되면 파일다이얼로그 창을 제공하고 선택된 LOG파일을 분석하여 위의 내용(1~6)을 Dialog에 출력하고, report생성 버튼은 view버튼이 한번이라도 클릭된 이후에 동작한다. report 클릭되면 c:/dev/report 폴더를 생성한 후 “report_생성날짜.dat” 파일을 생성하여 1~6까지의 작업을 모두 출력한다. 

 파일명(sist_input_1) log ( 생성된 날짜 년-월-일 시간:분:초 )
1.	 최다 사용키 : java xx회
2.
3.
4.
5.
  6. 1000~1500번째 정보 


위의 각 작업은 ID,PASSWORD 가 ‘admin,1234’, ‘root, 1111’로 로그인 했을 때에만 가능합니다.- 로그인이 성공했을 때 

(List, Set, Map 을 사용할 것)

-class diagram을 그리고, 코드리뷰를 위해 자신이 담당한 업무의 Flowchart를 작성할 것.
- 실행 가능한 jar로 만들어 배포할 것.
