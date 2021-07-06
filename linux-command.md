# CLI 명령어

Unix 명령어를 학습합니다.

---

## 단축키 명령어

|명령어|설명|
|:----:|:-:|
|`Ctrl + C`|취소|
|`Ctrl + L`|터미널 청소|
|`Ctrl + W`|단어 삭제|
|`Ctrl + D`|터미널 종료|
|상하 방향키|이전/다음 명령어 불러오기|
|좌우 방향키|커서 이동|

---

## 프롬프트 (prompt $)

터미널의 `$` 마크는 명령어 입력 준비 완료를 의미한다.
즉, `$` 마크가 없을 경우에는, 명령어를 입력해도 제대로 동작하지 않습니다.

---

## 폴더

폴더는 단순히 파일/폴더를 묶어줍니다.

### 폴더 생성하기

```sh
$ mkdir <dir_name>
```

### 폴더 이동하기

```sh
$ cd <dir_name>
```

### 폴더 삭제하기

```sh
$ rm -r <dir_name>
$ rm -rf <dir_name>
```

---

## 파일

### 파일 생성하기

```sh
$ touch <filename> # 확장자까지 반드시 작성
```

### 파일 삭제하기

```sh
$ rm <filename>
```

### 파일 실행하기

```sh
# Windows
$ start <filename>

# MacOS
$ open <filename>
```

---

## 복사/이동

### 복사

```sh
$ cp <original_name> <copy_name>
```

### 이동

```sh
# 이름 변경
$ mv <original_name> <another_name>

# 이동
$ mv <original_name> <another_path>
```

---

## Vim 편집기

