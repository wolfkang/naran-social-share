# 나란 소셜 공유 플러그인

워드프레스 포스트를 손쉽게 공유해 주는 플러그인입니다.


## 사용법
여타 플러그인처럼 설치 후 활성화시키면 됩니다.

관리자 > 소셜 공유 메뉴로 이동하여 적절히 설정하면 됩니다.


## 템플릿 변경
플러그인의 `includes/templates/buttons.php`는 플러그인의 기본 소셜 공유 링크(버튼)의 
출력을 위한 템플릿입니다. 주석에 쓰여진대로 기본으로 주어지는 PHP 변수를 활용하여 
원하는대로 HTML 구조를 찍어내면 됩니다.

이 때 플러그인의 템플릿을 수정하기보다, 템플릿을 오버라이드하세요.

테마 디렉토리에 'nss'라는 디렉토리를 만들고 'buttons.php' 파일을 복사합니다.
즉, `{테마 루트}/nss/buttons.php` 파일을 원하는대로 수정하시면 플러그인보다 테마의 파일을
우선하여 읽어들일 것입니다.
