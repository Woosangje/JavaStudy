# JavaStudy
(int ... values)<br/>
myCom.sum2(1,2,3,4,5); 로 ... 는 배열이 아니더라도 선언할수 있다.<br/>

★ 싱글턴 복습하기<br/>

클래스에사용할 만한 네이밍<br/>
show,  print , find, select, search , view, on<br/>
 get, set, add, create,<br/>


onCreate()<br/>
.execute<br/>
 addGroup , .addComponent , .addGap , .addContainerGap()<br/>
setItemName, onCreateView, onResume(), onPause(일시중지 null ),<br/>
onDestroyView(), stopData(), resetData, register<br/>
 initiate<br/>

12/22<br/>

c생성, r읽기 u수정 d삭제<br/>
Create  Read  Update  Delete<br/>

DB pk, bno, mbo(맴버번호)<br/>
상속은 Extended 로 클래스 이름짓는다.<br/>


★ 변조: 이름 중간글자를 *로 표시  (get메소드에서 설정)<br/>
카페(중고나라) > 웹크롤링(로봇이 알아서 웹의 정보를 가져감)<br/>
g*****@naver.com 으로 되어있지만 "연락처 보기"에서 제대로된 이메일을 볼수 있다.<br/>

상속에는 재정의가 있다.<br/>

★계좌번호 java파일 변경하기<br/>

스마트폰 만들기
스마트폰 용 메뉴 만들기

super();는 생략될수 있으며<br/>
★자식 클래스에서 사용자생성자 선언시 매개변수에 <br/>
super에다 선언할 매개변수도 선언해야한다.<br/>

정상범위에 있는 것이 무결성이 있는것<br/>
정상범위에 없으면 무결성오류<br/>

기타 메소드는 main아래에다 생성하면 된다.<br/>
★ 빌드오류시 객체용 클래스에 변수값 선언했는지 확인<br/>
자동타입변환, 강제타입변환<br/>

★ 메서드에 abstract 선언안해도 기본값으로 적용된다.<br/>
★익명메소드 선언방법<br/>

01/20<br/>
다음주 오라클 DB 마리아DB mysql<br/>
jsp<br/>

01/02<br/>
☆ 예외처리<br/>

cmd > nslookup > www.daum.net > 주소확인 > www.naver.com<br/>
e.printStackTrace();<br/>

tap(Run) > run configuration > Arguments > 입력<br/>

Surround With<br/>

XXXException 키워드를 사용해야한다.<br/>

// 사용자 지정 예외 처리<br/>
//필수 : 기본생성자 + 사용자지정생성자(메시지 전달)<br/>

Exception , Runtime<br/>

예외처리 계속 써먹음<br/>

사용자인터페이스는 안함(fx는 안함)<br/>

01/03
방예약 프로그램 (여기어때, 캠핏)

Scanner에 커서를 댄후 F1을 누르면 Help가 뜬다.
Class Scanner페이지로 이동하면 마우스 오른쪽클릭 > 주소 복사해서 웹브라우저에서 볼수있다.

//방법1 : Runnable 인터페이스를 사용하는 구현 클래스를 생성
implements Runnable
//방법2 : 다형성 -> Thread th = new Thread(Runnable target);

☆ deprecated 노란색물결 잘안쓴다는뜻

★★★ 동기화 메소드와 동기화블록
★★ 동기화 메소드 임계 영역 설정 예) user1과,user2가 갚이 같을경우
synchronized (this) 선언방법 해당 코드들을 드래그 > 마우스오른쪽 클릭> Surround With > 6. synchronized 클릭

다이아몬드 연산자

<T>는 "타입"이라 부른다.
제네릭
제네릭메서드, 실습

★★★★★★ 컬렉션 프레임 워크<br/>
배열보다 편하게 사용하려고<br/>
List 컬렉션 외우기 <br/>
clear()는 왠만하면 사용하지 않기 <br/>
contains<br/>

01/04 <br/>
★ 컬렉션 제네릭 자주 사용 <br/>
hashset는 순서가 없다. (반복문에서 입력순서와 일치하지 않음) <br/>
★ 하이라이트! Map 컬렉션 <br/>
.containsKey(id) <br/>

★ 프로퍼티파일만들기 <br/>
D:\workspace\java-304\src\ch14\list\map > properties라고 폴더생성 <br/>
택스트 생성 > 탭 보기에 확장명 체크할것 > txt파일명을 .properties로 변경 <br/>
메모장으로 텍스트 열어서 입력 <br/>
다른이름으로 저장 > 인코딩이 UTF-8 인지확인 & 모든파일형식으로 설정 <br/>
이클립스 ch14.list 오른쪽 클릭 > Refresh클릭하면 properties가 보인다. > <br/>
이클립스 properties에서 Exam생성 <br/>

람다식 은 메서드가 무조건 하나 <br/>
Invalid '@FunctionalInterface' annotation; MyFuncion is not a functional interface <br/>

로컬 변수는 실무에서 별로 안씀 <br/>

★ 컬렉션 중요 <br/>
사용자인터페이스 x안배울거임 <br/>

01/05
ch15.io <br/>
DB정보는 디스크에저장 <br/>
Stream 붙으면 byte 기반 <br/>
read()메서드는 int타입으로 간다. <br/>

// read(byte[8], 2(off), 3(len)) <br/>
// 8개의 배열을 선언하고 2번째부터 3개의 값을 가져온다. <br/>
void flush() 중요 <br/>
자바마스터489p 자주사용 <br/>

os.flush(); // 저장시 필수 1 <br/>
os.close(); // 저장시 필수 2 <br/>
 <br/>
부트스트랩 <br/>



0108<br/>
최종목적은 JDBC를 배우기 위함(Java + DB)<br/>

★ 네트워크형 데이터 모델 (취업하고도 공부해야함)<br/>

졸업 한달전까지 최종브로젝트는 스프링부트로 마리아DB이용해서<br/>
부장 부조장빼서 스프링을 이용한 프로젝트<br/>
나머지 사람들은 스프링을 이용해서 개인프로젝트<br/>
c언어 프로젝트, 파이썬 프로젝트<br/>

sql 배우면 mysql, mariadb에서도 사용할수 있다.<br/>

조회에는 두가지 선택적 조회, 전체 조회<br/>

★★★★x25<br/>
TCL(Transaction Control Language) 트랜젝션 데이터의 영구 저장 취소 등과 관련된 명령어<br/>

31p 읽기<br/>
기본키(pk)  유일한 값<br/>
후보키(null x , 유일o, 유관성o) <br/>
외래키(다른table의 기본키)  ★★★★★<br/>
복합키<br/>

오라클 실행시 메모리 가8이어야 한다.<br/>
10-3DB용<br/>
File > new x 새로 윈도우 설치 시간걸려서 안할거임<br/>

10-1 > D > workspace > 304복사옮겨라<br/>

10-1 탭에서 clone > 정품 >  아래 pull설정 > 이름 10-3(Oracle)로 변경<br/>
오른쪽 하단 에서 " ip설정 편집"  101을 103으로 수정<br/>
왼쪽 하단 시작 > 시스템 > 10-3으로 이름 바꾸기 > 다시시작<br/>

게임같은거 깔은 pc는 권장하지 않음<br/>

이번시간에는 OracleEnterPrise & Toad 를 사용 <br/>
10-3바탕화면에다가 2개의 파일 붙여넣기<br/>
나중에 OracleExpress 사용 <br/>
Toad는 유료 <br/>

10-3에서 OracleExpress > setup클릭 >그냥 예 > 이메일입력안함 ><br/>
데이터베이스 생성 및 구성 > 데스크톱 클래스 > <br/>
전역 데이터베이스 이름(G) 외우기 " orcl "<br/>
패스워드는 임시로 oracle > 예 > 완료<br/>
.NET Framwork 3.5 설치하기<br/>
잘깔렸는지 확인하는법 cmd들어가서 sqlplus system/oracle 입력후 정보뜨는지 확인<br/>

★ 키에 대한거 중요함<br/>

sqlplus DB 접속명령어<br/>

스콧이라는 사용자 계정을 바꾸겟다.<br/>

ACCOUNT Unlock 계정을 풀어라<br/>

connext scott/tiger;<br/>
exit;<br/>

☆ <br/>
; 만 넘어간다.<br/>
오타나면 그냥 세미콜론으로 enter치기<br/>

desc emp; //자주사용<br/>
VARCHAR2는 한글안된<br/>
N이붙어야 한글가능<br/>
NUMBER(숫자7개 , 소수점 2자리<br/>

select * from emp;<br/>

DESC 기억하기<br/>
DB를 편하게 사용하려고 TOAD사용<br/>

★ 토드 설치(KEY)
관리자 권한으로 실행 > 전부 INSTALL > 설치다되면 개구리보임<br/>
Toad for Oracle 13.1.1 > Skip This Version(업데이트 하지않기)<br/>
> ORCL > Save password > Add Login Record ( 아이디랑패스워드 소문자)<br/>
왼쪽상단 탭 콘센트 이미지 아이콘 클릭 > 계정이랑 database 입력<br/>

저장할까요 질문한 내용은 DB가 아닌 메모장에 저장되는것<br/>
desc emp; 입력후 드래그 ctrl + enter<br/>
★ 오라클 잘지워야 한다.<br/>
* 는 모든것을 대체<br/>
emp의 모든것을 가져와라<br/>

외울거 있음 [select 필드 , * ] from [테이블] where [조건문] ;<br/>
where는 조건문<br/>

★★★★ 조인 대게중요<br/>
열조회 4-4<br/>
IDSTINCT, 셀연산식<br/>
쌍따음표 4개사용할경우 내부 따음표는 따음표로 변경<br/>
정렬할때 <br/>
BETWEEN A AND B A에서 B까지<br/>
Like연산 자주 사용<br/>
123p쭉하고 외우기<br/>
연습문제도 풀어보기<br/>
하면서 주석달기 주석은 -- (단축키는 ctrl + B)<br/>
자바 붙일때 집중해야한다.<br/>

01/09
like 자주쓰임, 실습할때는 express설치할거임<br/>
express에는 SCOTT 계정이 없음<br/>
208P 해보라고 하면 이해잘 못함<br/>
PIVOT은 행렬을 뒤집어버리는거<br/>
UNPIVOT은 뒤집었던걸 원복하는거<br/>
★ 여러테이블을 하나의 테이블처럼 사용하는 조인<br/>

듀얼 = 버츄얼<br/>
듀얼은 실체는 없음 가짜로 테스트용으로 빼는 가짜 테이블<br/>

ERD<br/>
토드 > 탭 DATABASE > REPORT > ER<br/>
콘센트 아이콘에서 SCOTT계정확인 > 민트색 + 아이콘 누르고 4개다 체크하고 OK<br/>

★ scott이미지 참조하기<br/>
inner 조인이 제일중요 (다른테이블에서 당겨오는게 중요)<br/>

하나의 테이블을 2개 만든다.(자기 직원번호, 선임 직원번호)<br/>
ename이 king은 직급이 최고라 사원번호가 없음<br/>

오라클138P 214p까지 나중에진행<br/>
 240p까지 조인이해되면 08-3조인<br/>
조장이 join용으로 문제 5개 제출 다같이 풀어보자<br/>


