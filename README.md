## git config --global user.name "이름"

## git config --global user.email "깃허브 메일주소" // 매번 물어보는 귀찮음을 피하기 위해 설정.

## mkdir ~/MyProject   _// 로컬 디렉토리 만들고_

## cd ~/myproject      _// 디렉토리로 들어가서_

## git init            _// 깃 명령어를 사용할 수 있는 디렉토리로 만든다._

## git status          _// 현재 상태를 훑어보고_

## git add 화일명.확장자  _// 깃 주목 리스트에 화일을 추가하고 or_

## git add .           _// 이 명령은 현재 디렉토리의 모든 화일을 추가할 수 있다._

## git commit -m “현재형으로 설명” _// 커밋해서 스냅샷을 찍는다._


## git remote add origin https://github.com/username/myproject.git _// 로컬과 원격 저장소를 연결한다._

### git remote -v _// 연결상태를 확인한다._

## git push origin master _// 깃허브로 푸시한다._
