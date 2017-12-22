## - Git hub 오류 시 해결방법

### CASE 1

~~~Ruby
error: src refspec master does not match any.
~~~

* 위의 에러가 발생했을 시 다음의 코드를 작성한다.

~~~Ruby
git commit -m "initial commit"

git push origin master
~~~



###  CASE 2	

~~~Ruby
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
~~~

* 위의 에러가 발생했을 시 다음의 코드를 작성한다.

~~~Ruby
git config --global user.email my_email@email.com
git config --global user.name my_name
~~~



