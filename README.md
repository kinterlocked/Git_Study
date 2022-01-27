Git and GitHub Study<br>
<br>
맥에서 기존 GUI방식으로 쓰던 Git을 CLI방식으로 사용하기 위한 연습 및 테스트<br>
<br>
1일차<br>
Git의 간단한 push 메커니즘과 명령어<br>
git clone "URL주소" // GitHub repositories를 내 PC롤 clone<br>
git add "파일이름" // untrack인 파일을 신뢰할 수 있는 track파일로 추가<br>
git status를 입력시 현재 Git의 상태가 확인이 가능하다 // untrack파일은 red, track파일은 green<br>
git push origin main // GitHub로 push (push를 해버리면 되돌릴 수 없으니 주의)<br>
<br>
2일차<br>
Git은 처음 사용전 로그인이 필요하다<br>
홈페이지 로그인이 아닌 PC에 설치되어있는 Git에 로그인<br>
GitHub의 username을 변경할 경우 설정을 다시 해주어야 한다<br>
<br>
CLI를 처음 사용하여 push를 진행하는 경우 username과 password입력 필요했다<br>
username 입력후 password는 정책 변경으로 인해 발급받았더 토근값을 입력해야 한다.<br>
<br>
CLI방식으로 1번째 테스트때 username과 password를 입력했고<br>
2번째 테스트때는 별도의 입력없이 바로 push가 되는 것으 확인했다.<br>
<br>
3일차 <br>
똑같은 repositori를 clone한 후 기존파일을 지우고 새 파일을 추가한 후 push를 해보았다<br>
기존의 파일들이 삭제가 되는 것인지 확인하기 위함이었고 3번 째 push를 했을 때<br>
기존 파일은 그대로 있고 새로운 파일이 추가가 된 것으 확인하였다.<br>
4일차에는 폴더와 그 안의 파일들의 대한 push결과르 확인할 예정이다.<br>
