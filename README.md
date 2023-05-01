# github_connect

## 🌱 [깃설치](https://git-scm.com.download/win)
   -깃에 올려야 할 폴더에 가서 shift+우클릭 하여 '여기에 PowerShell 창 열기' 클릭
   
      git을 통해서 github과 연결할 수 있다.

   
      git init 
   -.git 폴더가 생성됨
      
---------------

## 2. 깃 설치 후 Git bash 열기
![image](https://user-images.githubusercontent.com/129016953/235417851-d323af2b-ab6d-4bf7-879f-66210e661d2a.png)

* 유저 이름 설정하기
         git config --global user.name "3dodam"
* 유저 이메일 설정하기 (반드시 github에 가입했던 이메일 주소와 동일해야한다)
         git config --global user.email "vesper1024@gmail.com"
* 내 정보 확인하기
         git config --list
         
## ⬆️ 위의 연결은 해당 컴퓨터에서 한번만 실행하면 됨
-----------------------------------------------
* 초기화
         git init
* 추가할 파일(폴더 안의 내용을 모두 올림, .은 모든 파일을 의미)
         git add .
* 히스토리 만들기(-m은 메시지를 의미함, "" 안에는 히스토리 이름을 적음)
         git commit -m "first commit"
* github의 repository를 만들고 그 주소와 연결하기
         git remote add origin https://github.com/3dodam/CssFlex.git
* 연결이 잘 되었는지 확인하기 (사용 안 해도 됨)
         git remote -v
* github에 올리기
         git push origin master
