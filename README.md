# gitEx
🖍 git, github 공부하는 리퍼지토리

## git branch 연결하기
### velog에서 보기 👇
[![Velog's GitHub stats](https://velog-readme-stats.vercel.app/api?name=55soup&slug=git-리퍼지토리-재연결)](https://github.com/eungyeole/velog-readme-stats)

### 리퍼지토리 연결 확인
```git
git remote -v
```  

현재 리퍼지토리 어디에 연결되어있는지 확인한다.
연결되어있는게 없다면 아무것도 출력되지 않고,
있다면 다음과 같이 나온다.

현재 나는 연결할 리퍼지토리가 따로 있는데, **새로 리퍼지토리가 생성**되면서 연결이 되었다.ㅠㅠ
<br>
<br>
### 리퍼지토리 연결 끊기
```git
git remote remove origin
```
내 분기이름은 origin이어서 다음과 같이 끊었다. 
**끊은 후 git remote -v로 확인!**


### 리퍼지토리 재연결
```git
git remote add origin [링크]
```  
<br>
<br>

### 연결 확인하기
![](https://velog.velcdn.com/images/55soup/post/ecee48a5-66b9-4fcc-884c-044ebf35e221/image.png)  
링크부분은 리퍼지토리를 들어갔을 때 다음 링크를 붙여넣으면 된다.  
<br>
<br>
![](https://velog.velcdn.com/images/55soup/post/55232097-0edb-487b-8747-4eede062511a/image.png)  
잘 연결된 모습이다.

---

### 참고하기! 
[원숭이에게 배우는 git](https://backlog.com/git-tutorial/kr/)

이슈 가져오기
