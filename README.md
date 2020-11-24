# **Lucene & Lire**
---
####Lucene(루씬)
---

 1. Lucene(루씬) 이란?
	  - 자바로 개발된 오픈소스 정보검색 라이브러리 (검색 애플리케이션이 아니다.)
	  - 아파치 재단의 오픈소스 프로젝트
	  - Full Text 의 색인 및 검색 기능
	  - 다운로드: https://lucene.apache.org/
      
 2.  Demo Example
1. jar 파일 4개 Lucene 폴더에 복사
	- lucene-queryparser-8.7.0.jar
	- lucene-analyzers-common-8.7.0.jar
	- lucene-core-8.7.0.jar
    - lucene-demo-8.7.0.jar

2. jar 압축 풀기 (4개 다)

		`jar xvf {파일명}.jar`
	
    - ex) jar xvf lucene-demo-8.7.0.jar
    - Lucene 폴더에 org, META-INF 폴더 생성됨
    <img src = "../img/jar.png">
    

3. 색인 할 txt file 을 Doc 파일에 생성
	- ex) NOTICE.txt, README.txt
	
4.  Index 생성
	
		    java org.apache.lucene.demo.IndexFiles -docs Doc(색인할 문서가 있는 폴더)

		<img src = "../img/index.png">
		<img src = "../img/index2.png">
		

5.  검색
	     ` java org.apache.lucene.demo.SearchFiles`
    - 검색할 string 입력
		 <img src = "../img/search.png">
 
 