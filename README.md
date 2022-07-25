# GuestBook

## GuestBook API 규격서
| Method | URI | Description |
| --- | --- | --- |
| Get | /guestbook/list | 리스트 조회 |
| Post | /guestbook/register | 방명록 남기기 |
| Get | /guestbook | redirect : /guestbook/list |
| Post | /guestbook/remove | 방명록 삭제 |
| Get | /guestbook/read | 방명록 읽기 |
| Post | /guestbook/modify | 방명록 수정 |
| get | /guestbook/list | 검색기능 |
| Get | /guestbook/list(page= ${result.end + 1} | 다음 페이지 |
| Get | /guestbook/list(page= ${result.start -1} | 이전 페이지 |


# GuestBook 설명

간단한 방명록이다. 

![image](https://user-images.githubusercontent.com/109207727/180783308-a653bb46-16f9-4d25-b462-0f067386c02f.png)


### register 버튼을 누르면 아래와 같은 창이 뜬다. 여기서 방명록을 작성할 수 있다.

![image](https://user-images.githubusercontent.com/109207727/180783467-7ca88d14-3681-4c12-afa8-19ac8a601ea6.png)

### 검색의 종류는 아래와 같다.

![image](https://user-images.githubusercontent.com/109207727/180783616-4a9309b7-e114-4e3d-8380-db2154c13b6b.png)
![image](https://user-images.githubusercontent.com/109207727/180783690-7b68d47b-497d-4fe2-9b87-3fd9e2af41a4.png)

### 글의 수정페이지를 들어가면 삭제 및 수정을 할 수 있다.

![image](https://user-images.githubusercontent.com/109207727/180783888-9a17a561-66b8-45bb-b90e-f2a693f032fc.png)
