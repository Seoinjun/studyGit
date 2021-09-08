
# Ch02 Branch: 가지치기

## 2.1. introduction
* version1에서 version2를 복사해서, 실험하는 상황
  1. ersion2 실험이 잘 되서, version1을 ver2로 바꾸려 한다고 가정하자.
  2. 일반 폴더에서 이 작업이 이루어질 경우, 병합처리하기 복잡하다.
  3. 이러한 상황을 고려해서, git에서 branch로 ver1과 ver2를 관리하고, 병합할 수 있다.

## 2.2. Create new branch
* defalut로 'master' branch가 있다고 가정하자.
  1. master에서 version1 파일을 만든다.
  2. sourceTree에서 click the new branch button.

## 2.3. Merge branch
  1. ver1과 ver2
  
## 2.4. merge error 해결
* 중복되는 영역에서 ver1과 ver2가 수정했을 때, merge하면 conflict 발생
  1. 해당 파일 열고, 직접 정리한다.
  2. sourceTree의 History 영역에 conflict난 파일이 표시되는데,
  3. 해당 파일의 오른쪽 클릭 > resolve conflict > Mark resolveed 
