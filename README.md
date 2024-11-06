# hustoj-bs5
hustoj를 부트스트랩 디자인 탬플릿을 이용하여 수정하였습니다.
- monaco 에디터를 사용하였습니다.
- problem_import_xml.php이 빠져있어서 추가했습니다.
- problemset.php수정하여 문제목록 디자인을 개선했습니다.
- gemini api를 활용하여 AI문제 출제 기능을 넣었습니다.
- 관리자페이지에서 설정파일을 직접 수정할 수 있습니다.
- 업데이트 기능을 추가하였습니다. github에서 release버전을 검사하여 업데이트를 수행합니다.
  - web 이하 디렉토리의 소유권을 변경하셔야 동작합니다.
  ** chown -R www-data:www-data /home/judge/src/web
