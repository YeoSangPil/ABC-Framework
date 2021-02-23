# ABC-Framework
##### -AntBot Community 사이트에 있는 프레임워크를 사용하기 편리하도록 수정하였습니다.
##### -원본은 https://antbot.co.kr/antbot/ (AntBot Community)에서 다운 받으실 수 있습니다.

## 프레임워크 파일구조

### 1. Component

  #### 프레임워크에서 사용되는 기능이 저장되는 디렉터리 입니다.
  #### <파일정보>
  ##### -capcherErrorScreenshot.xaml: 에러화면을 캡쳐하는 기능입니다.
  ##### -checkProcessRun.xaml: 프로세스가 실행중인지 체크하는 기능입니다. 실행중이지 않으면 오류를 발생시킵니다. (사용X)
  ##### -cleanDownloadPath.xaml: 프로젝트경로\Download 폴더안에 존재하는 모든 파일,폴더를 삭제하는 기능입니다.
  ##### -getConfigure.xaml: 프로젝트경로\Config\환경설정.xlsx 의 설정정보를 읽는 기능입니다.
  ##### -sendErrorMail.xaml: 프로세스 실행중 에러발생시 에러메일을 보내는 기능입니다.
  ##### -stopProcess.xaml: 프로세스 실행 및 재시도시 실행중인 프로세스를 종료하는 기능입니다. 강제종료이기 때문에 진행사항이 저장되지 않을 수 있습니다.

### 2. Config

  #### 설정파일이 저장되는 경로 입니다.
  #### <파일정보>
  ##### -환경설정.xlsx: 프레임워크, 프로세스에서 사용할 설정정보를 저장하는 엑셀파일입니다.

### 3. Download

  #### 

### 4. ErrorScreenShot
### 5. File
### 6. imagesave
### 7. Process
### 8. antMain.xaml

### Update 이력
2021-02-23: 에러화면 캡쳐 로직을 컴포넌트로 분리 및 오류 수정
