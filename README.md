# Backend_Script3_WebSite_app


進入虛擬環境後。


創建資料夾


          mkdir dir_name


導航至資料夾

          cd dir_name
          
          
在資料夾下層建立 專案

        django-admin startproject proj_name
        

打開專案 會看到結構如下  

          cd proj_name 

                       /locallib	 manage.py
     
        
不導行在專案下建立 目錄清單

        python3 manage.py startapp catalog
        
        專案下目前擁有的下層夾層有：
        
                      /locallib	 manage.py catalog
                      
                      其中 catalog 擁有 apps 註冊 和 資料模組 與視覺畫面邏輯控制器 
                      
                          __init__.py	apps.py		models.py	views.py  admin.py	migrations	tests.py
                      
                      
                      同層 locallib 擁有 url
                      
                         __init__.py	asgi.py		settings.py	urls.py		wsgi.py
        


                
Sample


              (p0207) KatesAndroiddeMacBook-Pro:test0207 katesandroid$ mkdir locallib
              (p0207) KatesAndroiddeMacBook-Pro:test0207 katesandroid$ cd locallib
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ django-admin startproject locallib
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ cd locallib
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ ls
              locallib	 manage.py
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ cd locallib
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ ls
              __init__.py	asgi.py		settings.py	urls.py		wsgi.py


              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ cd ..
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ ls
              locallib	manage.py
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ python3 manage.py startapp catalog
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ ls
              catalog		locallib	manage.py
              (p0207) KatesAndroiddeMacBook-Pro:locallib katesandroid$ cd catalog
              (p0207) KatesAndroiddeMacBook-Pro:catalog katesandroid$ ls
              __init__.py	apps.py		models.py	views.py
              admin.py	migrations	tests.py
              (p0207) KatesAndroiddeMacBook-Pro:catalog katesandroid$ 
