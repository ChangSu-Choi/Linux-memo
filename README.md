# Linux-Commend

> ## ssh
> *Connect to the server.*  
> |제목|내용|
> |------|---|
> |-a|인증 에이전트 전송을 불허|
> |-e|세션에 대한 이스케이프 문자를 설정|
> |-f|인증과 전송이 설정된 후에 백그라운드에서 ssh를 설정|
> |-l|원격 시스템에 사용할 로그인 이름을 설정|
> |-p|원격 호스트에 연결할 포트를 지정|
> |-v|디버깅모드 자세한 정보 표시 모드를 활성|
> |-x|X11 전송을 불가능하게 설정|
> |-L|지정된 원격 호스트와 포트에 전송할 로컬 포트 설정|
> |-R|로컬 호스트와 지정된 포트로 전송될 원격 포트 설정|
> 
> If you change the port, designate it and connect.
> + `$ ssh [remote account]@[server ip] -p [port to change]`
> 
> It is also possible to input a command to be executed immediately after remote access.  
> + `$ ssh [remote account]@[server ip] [commend]`
> 
> How to logout
> + `$ logout`
  
![image](https://user-images.githubusercontent.com/44316561/152780057-0828802a-771a-41b9-b267-05000863eff6.png)
  
> ## chmod
> *If you got the messages 'Permission denied' check the permission*
> Add all permissions for users, groups, and others.  
> + `$ chmod 777 [destination of file or folder]`
> give all permission to users, Give the group and others read-only access  
> + `$ chmod 744 [destination of file or folder]`  
> r w x  
> 4 + 2 + 1 = 7  

> ## chown, chgrp
> *Change owner*
> + `$ chmod 777 [destination of file or folder]`
> *Change chgrp*
> + `$ sudo chgrp -R [destination of file or folder]`
> r w x  
> 4 + 2 + 1 = 7  

 
> ## scp
> `$ scp -P [port number] [local path] [username]@[server ip]:[destination path]`
