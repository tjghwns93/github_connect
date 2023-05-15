# github_connect

## 1. 🛀 [깃설치](https://git-scm.com/download/win)

      git을 통해서 github과 연결할 수 있다.
      git init

-깃에 올려야할 폴더에 가서 shift + 우클릭하여 PowerShell창 열기




- .git 폴더가 생성됨
------------------
## 2. 깃 설치 후 git bash 열기

![image](https://user-images.githubusercontent.com/129016977/235418160-2616dd0e-8e32-45ea-9a25-5dd6a81cf03f.png)

* 유저 이름 설정

             git config --global user.name "tjghwns"

* 유저 이메일 설정하기(반드시 github에 가입했던 이메일주소와 동일해야한다)

             git config --global user.email "your_email"
             
* 내 정보 확인하기

            git config --list



## ⬆️ 위의 연결은 해당 컴퓨터에서 한번에 실행하면 됨
-------------------------

# github에 코드 업로드하기

   * 초기화
   
                  git init
   
   * 추가할 파일(폴더 안에 내용을 모두 올림, .은 모든 파일을 의미)
   
                  git add .
                  
   * 히스토리 만들기(-m 은 메세지를 의미함 ""안에는 히스토리 이름을 적음)
   
                  git commit -m "first commit"
      
   * Github의 repository를 만들고 그 주소와 연결하기
   
                  git remote add origin https://github.com/tjghwns93/css_flex.git

   * 연결이 잘 되었는지 확인하기(사용 안해도 됨)

                  git remote -v
                  
   * Github에 올리기
                  git push origin master

----------------------------------
## 수정하여 다시 업로드할 때 

1. 기존의 코드를 다운받는 행위를 해야한다.

        git pull origin master
        
2. 다시 push 해야한다.

        git push origin master 
        
        
----------------------------------------------------
# github 협업하는 방법





# 사원입장---------------------------------------------------


1. 소스코드 다운로드
   git clone 주소
   
   git clone https://github.com/tjghwns93/hanacard.git
   
2. 브랜치(branch) 만들기

   git checkout -b 브랜치이름
   
   git check -b seo
   
   git add .
   
   git commit -m "하나카드"
   
   git push origin 브랜치이름
   
   git push origin seo
   
   ![image](https://github.com/tjghwns93/github_connect/assets/129016977/33a6c7b4-8a5d-4cfa-b5a1-66734fd382f1)

