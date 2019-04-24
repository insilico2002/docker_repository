django 프로젝트 프레임
=============

개발 요구사항 (필수)
-------------
- docker
- python3.6
- virtualenv

개발환경
-------------

- mysql 5.7
- django 2.0.5
- djangomako 1.1.1


개발환경 구축 방법
-------------

- <code>mkdir workspace</code>    
- <code>cd workspace</code>    
- <code>git clone https://github.com/h4ppyy/main</code>    
- <code>cd main</code>    
- <code>make venv</code>  
- <code>. venv/bin/activate</code>  
- <code>make req</code>  
- <code>make db</code>  
- <code>make mig</code>  
- <code>make sql</code>  
- <code>make server</code>  
  
접속 방법
-------------
- django  
127.0.0.1:7777/sample  
- mysql  
127.0.0.1:3315  

브랜치 정보
-------------
##### version1
- 기본 프레임

##### version2
- 디렉토리 모듈화

##### version3
- vue.js + axios 샘플 추가

##### version4
- vue.js + axios + drf + mysql 'CR' 샘플 추가

##### version5
- 개발환경 자동화 (Makefile, docker)

##### default
- 이 브랜치를 가장 많이 사용할거에요 (경량화)

# docker_repository
