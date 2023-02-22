# git-flow-practice
![image](https://user-images.githubusercontent.com/70135188/220683311-bdfad0ed-d841-447f-ae8c-1dfea2f3188e.png)

해당 깃 플로우 연습.

merge시 커밋로그가 나오지 않았다. 그 이유는 Fast-forward 병합 때문인데

병합하려는 브랜치가 현재 브랜치의 직전 커밋에 기반한 새로운 커밋을 생성하지 않고, 그냥 이동하는 경우이다.

이런 경우, git merge 명령어를 실행하면 merge 커밋이 생성되지 않았다.

## Soution
$ git merge --no-ff feature -> --no-ff 옵션을 사용해서 그냥 이동 하지않고, merge시 커밋로그를 생성해줬다. 
