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
c생성, r읽기 u수정 d삭제  Create  Read  Update  Delete<br/>

DB pk, bno, mbo(맴버번호)<br/>
상속은 Extended 로 클래스 이름짓는다.<br/>

★ 변조: 이름 중간글자를 *로 표시  (get메소드에서 설정)<br/>
카페(중고나라) > 웹크롤링(로봇이 알아서 웹의 정보를 가져감)<br/>
g*****@naver.com 으로 되어있지만 "연락처 보기"에서 제대로된 이메일을 볼수 있다.<br/>

상속에는 재정의가 있다.<br/>
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
다음주 오라클 DB 마리아DB mysql jsp<br/>

01/02<br/>
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

다이아몬드 연산자 <T>는 "타입"이라 부른다.

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
DB정보는 디스크에저장 <br/>
Stream 붙으면 byte 기반 <br/>
read()메서드는 int타입으로 간다. <br/>

// read(byte[8], 2(off), 3(len)) <br/>
// 8개의 배열을 선언하고 2번째부터 3개의 값을 가져온다. <br/>
void flush() 중요 <br/>
자바마스터489p 자주사용 <br/>

os.flush(); // 저장시 필수 1 <br/>
os.close(); // 저장시 필수 2 <br/>
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

오라클 실행시 메모리가 8이어야 한다.<br/>
10-3DB용<br/>
File > new x 새로 윈도우 설치 시간걸려서 안할거임<br/>

10-1 > D > workspace > 304복사옮겨라<br/>

10-1 탭에서 clone > 정품 >  아래 pull설정 > 이름 10-3(Oracle)로 변경<br/>
오른쪽 하단 에서 " ip설정 편집"  101을 103으로 수정<br/>
왼쪽 하단 시작 > 시스템 > 10-3으로 이름 바꾸기 > 다시시작<br/>

게임같은거 깔은 pc는 권장하지 않음<br/>

●●● 이번시간에는 OracleEnterPrise & Toad 를 사용 <br/>
 10-3바탕화면에다가 OracleEnterPrise & Toad  파일 붙여넣기<br/>
 나중에 OracleExpress 사용, Toad는 유료 <br/>

10-3에서 OracleExpress > setup클릭 > 그냥 예 > 이메일입력안함 ><br/>
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

☆ ; 만 넘어간다  <br/>
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
★ BETWEEN A AND B A에서 B까지, Like연산 자주 사용<br/>
123p쭉하고 외우기<br/>
하면서 주석달기 주석은 -- (단축키는 ctrl + B)<br/>
자바 붙일때 집중해야한다.<br/>

01/09
실습할때는 express설치할거임<br/>
express에는 SCOTT 계정이 없음<br/>
208P 해보라고 하면 이해잘 못함<br/>
PIVOT은 행렬을 뒤집어버리는거<br/>
UNPIVOT은 뒤집었던걸 원복하는거<br/>
★ 여러테이블을 하나의 테이블처럼 사용하는 조인<br/>

듀얼 = 버츄얼,  듀얼은 실체는 없음 가짜로 테스트용으로 빼는 가짜 테이블<br/>

ERD<br/>
★ 토드 실행 방법: 토드 > 탭 DATABASE > REPORT > ER > 콘센트 아이콘에서 SCOTT계정확인 > 민트색 + 아이콘 누르고 4개다 체크하고 OK<br/>

★ scott이미지 참조하기<br/>
inner 조인이 제일중요 (다른테이블에서 당겨오는게 중요)<br/>

하나의 테이블을 2개 만든다.(자기 직원번호, 선임 직원번호)<br/>
ename이 king은 직급이 최고라 사원번호가 없음<br/>

오라클138P 214p까지 나중에진행<br/>
 240p까지 조인이해되면 08-3조인<br/>
조장이 join용으로 문제 5개 제출 다같이 풀어보자<br/>


01/10<br/>
Left Outer  join 자주사용<br/>
★ 09-1 서브쿼리, in연산자<br/>
240~263p까지<br/>
셀렉트문<br/>

★10-1<br/>
정의란 테이블이나 사용자, DB일수도 있음<br/>

Select, Insert, Update, Delete<br/>
Scott계정인지 확인 <br/>
ctrl + d눌러보기 > Specify > table > SCOTT > Object Name : BONUS<br/>
Object Name에서 4가지 전부 생성하기<br/>

Commit은 영구저장 Rollback은 돌아기기<br/>
'' 또는 NULL이 라도 넣어줘야 한다. ""는 널취급<br/>

create table DEPT_TEMP as select * from DEPT; --dept 사본 생성<br/>
drop table DEPT_TEMP ; -- 테이블 삭제용<br/>

289p까지 시간남으면 <br/>
프로젝트.hwp 금요일에시작?<br/>
★★★ 조작어 DML(외워야할 10가지)<br/>

Select  필드,*  from 테이블 Where 조건문 ;<br/>
Insert info 테이블명 value 값1,값2,값3...<br/>
update 테이블 Set 필드값 Where 조건 ;<br/>
Delete 	from 테이블 where 조건 ;<br/>

01/11<br/>
조장은 db의 권한을 공유하면 안됨<br/>
DDL에서 crud가 존재함<br/>
★DDL 정의(객체)<br/>
C DB create<br/>
R table select<br/>
U usdr alter<br/>
D	drop user<br/>

★DCL 제어<br/>
권한부여<br/>
권한제거<br/>
Commit<br/>
roll back<br/>

프로젝트.hwp<br/>
connect / as sysdba 가 아니라 sqlplus system/oracle<br/>
GRANT 는 권한부여<br/>

제약조건(constraint)<br/>

★ 364p 제약조건 실습 자주사용함<br/>
(이름이 없으면 오라클이 자동으로 만들어 준다.)<br/>
팀프로젝트할때 내가 한걸 ppt에 넣어야한다.<br/>
★ Foreign 키 중요 <br/>
CASCADE 되도록 사용하지 않는게 좋음<br/>

01/12<br/>
as null (자식은 null값처리)<br/>
★★★★ 사용자, 권한, 롤 관리 (중요)<br/>
처음에는 권한이 없음 조장이 connect 권한을 줘야 권한이 생김<br/>
DB는 24시간 동안 켜져있어야한다. 테이블이 많을수로 비용이 늘어난다.<br/>
패스워드1234하지 말것<br/>
팀명이 파일명<br/>
우선 시스템 계정은 cmd에서 하면 된다.<br/>
logine denied : 제한되어 있다.<br/>
아무것도 안뜨면 정보가 없는거<br/>
★★★★ 사용자 관리<br/>
casecade 모두 삭제하기<br/>
RESOURCE란 TABLE, VIEW SEQUENCE를 묶어 놓은것<br/>
조장, 부조장은 DBA권한을 가진다.<br/>
부원은 RESOURCE권하을 가진다.<br/>
CONNECT는 교사용<br/>
★객체권한이란 읽기<br/>
★★★★ 415P 중요<br/>
백업할 때 경로/파일명.dbf 옮기면 된다.<br/>
erd <br/>
항상 db부터 만들고 자바를 만든다.<br/>
pl/sql 안해도됨<br/>
★ 트리거<br/>
트리거를 적용한 db는 누가 회원정보를 삭제했다 하면 트리거에 회원정보가 남아있다.<br/>
DDL 트리거 조장,부조장이 주로 사용<br/>

실전예제 https://pinetreeday.tistory.com/212<br/>
중요한건 테이블 2개만든다<br/>
OLD테이블, 백업 테이블<br/>
PPT에 오라클 작업물을 넣는다.<br/>
396~415 / 롤<br/>
508 ~ 트리거 실습<br/>

조별로 스크립트 만들기<br/>
특수기호같은 경우는 파일명을 영어로 바꿔라<br/>

★ Database > ER_Diagram >초록색 + 누르고 select 토글 on해놓기<br/>

★ 부모키가 없습니다.<br/>
HS_PROFESSOR 갚넣어야 한다.<br/>


컴퓨터공학과, 디자인과, 우주공학과, 산업공학과, 오징어학과<br/>




ER
hs_lecture를 마지막으로
