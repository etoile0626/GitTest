#SE를 위한 실습

git init = 깃을 사용할거다, 초기화 작업

a나 i로 입력몯,
esc로 탈출


  fetch를 먼저하고 작업하는 걸 권장!
  branch == 줄기 같은 느낌? 작업의 흐름을 나눠서 진행이 가능
git checkout -b develop =>develop라는 브랜치를 생성하면서 이동!

git branch -a =>가지고 있는 모든 브랜치 확인 가능!
git merge (합칠 브랜치) => 현재 브랜치로 합칠 브랜치 병합시킴(브랜치는 전부 존재)

로컬에서 깃허브로 올리기 : git add ()=> git commit -m "코멘트" => git push origin (브랜치)
내려받기git fetch 후 git pull origin (브랜치)
push는 제일 마지막에! commit을 계속해주다가 작업을 마무리할때 push를 하고 건드리지 말기
