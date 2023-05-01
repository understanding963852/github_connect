# github_connect

##  1. ✈️ [깃설치](https://git-scm.com/download/win)  

      git을 통해서 github과 연결할수 있다.


 - 깃에 올려야할 폴더에 가서 shift + 우클릭하여 PowerShell창열기
                            
      git init
      
      
 - .git 폴더가 생성됨
 ---------------------
 ## 2. 🍎 깃 설치후 Git bash 열기
 
 ![image](https://user-images.githubusercontent.com/60366769/235417840-18a965b3-8a2e-4e55-bf57-4b69f988e763.png)
 
 * 유저 이름 설정하기
 
            git config --global user.name "suuneee"


* 유저 이메일 설정하기(반드시 github에 가입했던 이메일주소와 동일해야한다)
 
            git config --global user.email "suuneeee@naver.com"
      
* 내 정보 확인하기

            git config --list


##  ⬆️ 위의 연결은 해당 컴퓨터에서 한번에 실행하면 됨
----------------------------------

# github에 코드 업로드하기

   * 초기화 
       git init
   * 추가할 파일(폴더안에 내용을 모두 올림, .은 모든 파일을 의미)
       git add .
   * 히스토리 만들기(-m 은 메세지를 의미함 ""안에는 히스토리이름을 적음)
       git commit -m "first commit"
       
  * Github의 repository를 만들고 그 주소와 연결하기

            git remote add origin https://github.com/understanding963852/css_flex.git
            
  * 연결이 잘 되었는지 확인하기(사용안해도됨)    

            git remote -v
            
  * Github에 올리기
           git push origin master
