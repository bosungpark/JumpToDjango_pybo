# JumpToDjango pybo
> '점프 투 장고'를 보며 pybo 게시판을 구현하였습니다.

![image](https://user-images.githubusercontent.com/81157873/147243045-a787dcbf-be16-4470-a7f2-926b189672cd.png)

장고를 이용해 블로그를 만들어 보았습니다.

pybo 게시판은 숙련된 연습을 위해 총 3차례 구현하였는데, 이 문서는 그 중 2번째 작업입니다.

## 주요 기능

-CRUD의 구현

-탬플릿 상속과 앱 분리

-계정 관련 기능 구현

-페이지네이터 구현

-검색과 정렬 기능 구현

-댓글 및 대댓글 기능 구현

## 설치 방법

IDE는 VS Code를 기준으로 합니다.

깃에서 초기 파일을 내려 받는 방법 (VS code에서 빈 폴더 생성 후)

```
$ git clone https://github.com/bosungpark/JumpToDjango_pybo.git
```

가상환경 생성하기 및 켜기

```
$ cd venvs
$ python3 -m venv myvenv
$ source myvenv/bin/activate      //Mac
$ source myvenv/scripts/activate  // Windows
```

확인 및 실행

```
$ cd venvs
$ python manage.py runserver
```

## 사용 예제

1.자유롭게 글을 쓰고 삭제 및 수정을 할 수 있다.

2.원하는 게시물을 검색할 수 있다.

3.로그인 및 회원가입 기능을 이용할 수 있다.

4.원하는 기준으로 게시물을 정렬할 수 있다.

5.댓글 및 대댓글 좋아요 등의 기능을 이용할 수 있다.


## 개발 환경 설정

별도의 환경설정을 할 필요 없음

## 업데이트 내역

* 0.0.1
    * 작업 진행 중

## 정보

박보성 – [@블로그에서 영상 확인하기](https://blog.naver.com/qkrqhtjd0806/222419175647) – 이메일: qkrqhtjd0806@naver.com


## 기여 방법

1. (<https://github.com/yourname/yourproject/fork>)을 포크합니다.
2. (`git checkout -b feature/fooBar`) 명령어로 새 브랜치를 만드세요.
3. (`git commit -am 'Add some fooBar'`) 명령어로 커밋하세요.
4. (`git push origin feature/fooBar`) 명령어로 브랜치에 푸시하세요. 
5. 풀 리퀘스트를 보내주세요.
