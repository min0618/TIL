# 원격저장소(remote repository) 활용

> 원격저장소를 제공해주는 서비스 중에 GitHub를 활용

## 원격저장소 등록

```bash
$ git remote add origin <주소>
```

```bash
# 예시
$ git remote add origin https//github.com/min0618/first.git
```

* 깃(git)아, 원격저장소(remote)에 추가(add) 해줘, `origin`이라는 이름으로 <주소>를 

## 원격저장소 조회

```bash
$ git remote -v
origin  https://github.com/min0618/first.git (fetch)
origin  https://github.com/min0618/first.git (push)
```

## 원격저장소 삭제

```bash
$ git remote rm origin
```

* 깃(git)아, 원격저장소(remote)에 삭제(rm) 할게. `origin`을.

## push

```bash
$ git push origin master
```

* 깃(git)아, push할게. `origin`의 master로 

* 커밋 push함! 

  현재 폴더의 파일들을 업로드하는 개념이 아님! 
  
  ![333](md-images/333.jpg)

## Clone

```bash
$ git clone <url>
```

```bash
$ git clone https://github.com/hm0618/project1.git
```

