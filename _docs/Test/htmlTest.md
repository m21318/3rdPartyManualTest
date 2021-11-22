---
title: 로컬에서 php 디버깅
category: Test
order: 1
---


1. 아파치 서비스 시작 (*서비스 또는 apache monitor에서 실행 여부 확인 가능)
![Foo](/resource/Untitled.png)

1. php 파일은 루트폴더 밑 \map\svc\ngii에 있어야 합니다.aaaaaaaaa aaaaaaaaabbbbb
    ex) C:\Hanmac_Apps\MapService\Apache24\htdocs\map\svc\ngii
    
2. loginfo4test.php 파일의 DB 커넥트 정보를 연결할 DB에 맞춰 변경합니다.
![Foo](/resource/Untitled 1.png)

3. 테스트 서버로 연결한 경우 pixel 컬럼이 추가되어 있고 코드 수정 전 이므로 add.php의 INSERT 구문이 수정되어야 합니다.
![Foo](/resource/Untitled 2.png)

4. 디버깅 포인트를 잡고 F5 키를 눌러 실행합니다 . 하단 이미지에 표시된 부분을 확인해주세요.
![Foo](/resource/Untitled 3.png)
<p  style="font-size:250%">
마크다운 사이의 html 태그 확인
</p>
<h1 style="background-color:white; color:maroon; font-size:150%; text-align:center">
    style 속성 이용
</h1>

5. TopographicServerUploader 를 실행하여 필터를 선택하고 작업 디렉토리를 설정한 후 시작 버튼을 클릭합니다. (*코드 수정 전이므로 기존 경로에 맞춰 파일을 위치시켜주세요)
![Foo](/resource/Untitled 4.png)
    
6. 오류 등 이유로 같은 파일로 여러 번 테스트를 진행 할 경우 업로드 된 위치에 있는 파일과 작업 디렉토리의 하위 시도 폴더에 생성된 텍스트 파일을 삭제 한 후 테스트를 진행합니다.
![Foo](/resource/Untitled 5.png)
    