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

