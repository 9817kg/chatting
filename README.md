# chatting
chatting Program Project 


0714 < 11:05> 수정본 
0717 < 10:30> 이메일 인증 로직 / 기상청 (구) API 이미지 추가  <삭제>
07.19 < 14:46> WeatherBit API 일일 횟수 제한 50 
07.19 <이교진> 관리자 기능 ( 강퇴 ) 추가 
07.20 <Weather Class > 로직 if 문 경로 (MAC OS)
07.21 <이교진> 방 인원 수 0명일 경우 방 자동삭제.
07.21 <이승민> GaebalTalk내에 다크모드 라이트모드 아이콘 클릭 시 변환하는 클래스 추가해서 호출함. 색상은 여러색상 고민중. firstSwing                 로그인 후 닫는 방식도 변경.
07.21 <이교진> 채팅방 파일전송 추가
07.22 <이교진> 채팅로그 파일 중복생성 수정, 관리자 기능( 금지어 설정 )  기능 추가, 내가보낸 채팅, 귓속말 구분 추가
07.23 <이승민> 채팅방 각 버튼들 이미지 추가
07.23 <이승민> 라인정리, 각 아이콘들의 위치조절코드 수정, 설정 탭에 프로필지우고 NotificationScreen 클래스 추가(다크모드 관련 수정 중)
              fontSize 및 engFontSize 크기조절
              darkEngFontSize 및 darkFontSize 추가
07.23 <이승민> 위에서 문제있던 부분 수정 완료, darkCancel이미지 추가
07.23 <이승민> ChatClient 클래스 버튼들 이미지로 변경
07.24 <이승민> chatdb패키지 안에있는 모든 파일 규호 컴퓨터 바뀌면서 IP 14.42.124.97로 되어있던거 전부 14.42.124.13 으로 변경하고 DTO                 private로 되어있던거 이름, 전화번호, 아이디 등의 정보 빼오기 위해 public으로 수정
07.24 <이승민> FirstSwing에서 로그인 하면 그 로그인 한 사람의 DB정보를 받아오게 수정 함.
              닉네임 입력 삭제하고 채팅방에서 로그인한 사람의 이름이 나오게 수정 함.
              MemberDTO 변수 필드 선언하고 39라인에 globalUserDTO 라는 변수추가
              207라인! 220라인까지 GaebalTalk로 정보 전해주게 수정
              이미지가 너무 많아서 빼먹은게 있을까봐 전체 재업로드, 이름은 같아서 코드에는 영향없음.
              EngGaebalTalk 업데이트 및 EngDarkModeChanger 추가, EngVerFirstSwing 수정
              공지사항 내용란에 html태그를 사용하여 줄 바꿈이 가능하게 함.
              내용은 임시로 깃에 ReadMe에 있는 내용 그냥 갖다박아놓음
07.25 <이승민> ChatClient 클래스 내에 있는 컴포넌트들 각 위치를 기준으로 JFrame크기를 변경했을 때 그 비율에 맞춰 크기 조절되게함.
              GaebalTalk내에 ProfileSet 내부에 있는 되돌리기 버튼 추가가 안되어 있어서 DarkModeChanger에 cancelLb 이미지 추가
07.27 <이승민> GaebalTalk마무리 및 EngVer 다수 수정 및 추가 영어버전에 사용 할 이미지 추가. 
              오타 수정 및 JoinScreen, FindID클래스 등에서 textField내에 글자 색이 흰색으로 되어있는거 전체 수정
