# upgraded 폴더 구조 설명

`upgraded` 폴더는 레거시(`legacy`) 폴더의 모든 파일과 디렉터리 구조를 그대로 복사하여 생성된 폴더입니다. 각 파일과 디렉터리는 다음과 같은 역할을 가집니다:

- `MANIFEST.in`, `README.rst`, `setup.py`, `distribute_setup.py`, `distribute-0.6.10.tar.gz`: 패키지 메타데이터 및 설치 관련 파일
- `docs/`: 문서 및 Sphinx 빌드 관련 파일
    - `Makefile`, `source/`, `build/` 등
- `guachi/`: 주요 Python 모듈 및 테스트 코드
    - `__init__.py`, `config.py`, `database.py`, `tests/` 등
- `guachi.egg-info/`: 패키지 배포 정보 파일
    - `PKG-INFO`, `SOURCES.txt`, `top_level.txt`, `dependency_links.txt`

이 폴더는 레거시 프로젝트의 구조와 동일하게 업그레이드 작업을 위한 베이스로 활용됩니다.
