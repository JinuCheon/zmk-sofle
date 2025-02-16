### SOFLE 키보드 키매핑 소프트웨어

[이 블로그 보고 적용함] (https://blog.kxx.kr/memo/2024/12/22/sofle-keyboard-zmk-build-organize/)

1. 키맵 에디터에 가서, 현재 github 을 연동 (https://nickcoutsos.github.io/keymap-editor/)
2. 적용해서 저장하면 자동으로 push 되고, action 이 돌아감.
3. action 결과물 (Artifacts) 로 펌웨어 설정파일이 나옴
4. 설정파일 중 nice_view 로 시작하는 파일 두 개를, 각각 왼쪽 키보드 오른쪽 키보드에 넣어줌
5. 키보드 연결 후에 오른쪽 버튼 2 번 누르면 열림
6. mac os 기준 파일 복사해서 덮어쓰면 -36 에러가 나면서 튕김. 그러나 잘 덮어써졌으니 무시하면 됨.

### 현재 내 키 매핑
![스크린샷 2025-02-13 오후 11 38 21](https://github.com/user-attachments/assets/2002a6cf-c18e-4835-b0c9-0ee75f46c4c9)

![스크린샷 2025-02-13 오후 11 38 36](https://github.com/user-attachments/assets/aac5bb8d-3ebd-4800-9f50-3a53cce71999)

![스크린샷 2025-02-13 오후 11 38 42](https://github.com/user-attachments/assets/9ac787b3-71a6-410c-9fd3-050e8cc7078c)

### 그리고.. 기본 vim 사용
입력 모드 (Insert mode):
-	i → 현재 커서 위치에서 입력
-	I → 해당 줄의 맨 앞에서 입력
-	a → 현재 커서 다음 위치에서 입력
-	A → 해당 줄의 맨 뒤에서 입력
-	o → 현재 줄 아래 새 줄 추가 후 입력
-	O → 현재 줄 위에 새 줄 추가 후 입력

단어 및 줄 이동:
- w → 다음 단어 앞으로
- b → 이전 단어 앞으로
- e → 현재 또는 다음 단어 끝으로
- 0 → 줄 맨 앞으로
- ^ → 줄 첫 번째 글자로 이동
- $ → 줄 맨 뒤로

화면 이동:
- Ctrl-d → 아래로 반 페이지
- Ctrl-u → 위로 반 페이지
- Ctrl-f → 다음 페이지
- Ctrl-b → 이전 페이지


-----
- [中文](README.md)
- [English](README_EN.md)

# 更新列表

- 2024/12/21
  1. 增加zmk-studio支持（只需要刷新左手即可使用）。
- 2024/10/24
  1. 修改供电模式，功耗降低。
  2. 修正RGB供电自动关闭的功能。

> 如果您的键盘于10月24日之前更新，请更新最新的固件。
> 
---
# 联系我

如需3D打印的模型文件或者键盘有任何异常和故障，请联系380465425@qq.com

# Sofle键位图

<img src="keymap-drawer/sofle.svg" >
.
