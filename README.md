# WordCount
Likelion 8th Coding Section

### Code

```
$ python3 --version // 파이썬 3 버전 확인

$ pwd // 현재 디렉토리 위치

$ Python3 -m venv myvenv // myvenv라는 가상환경을 만든다.

$ source myvenv/bin/activate // myvenv 가상환경을 실행한다.

$ pip install django // django를 설치한다.

$ python -m pip install --upgrade pip // pip를 upgrade한다.

$ django-admin startproject firstprj

$ cd [디렉토리명] // 해당 디렉토리로 이동

$ python manage.py runserver // manage.py의 서버를 실행한다.

$ python manage.py startapp [App이름] // App을 시작한다.

```

**Hello version**
```
apps.py -> class 명 확인 (HelloConfig) -> setting.py에서 Installed_APPS에 app 경로를 추가하기

views.py : 
def home (request):
    return render(request,'index.html')
//home이라는 함수를 정의하고 이는 request와 index.html을 render한 값을 반환한다.

urls.py :
import Hello.views // Hello라는 디렉토리에 views.py파일을 유입한다.
urlpatterns = [
    path('admin/', admin.site.urls),
    path('', Hello.views.home, name = 'home'), 
]
```



### 
 
