## **SELECT**
데이터 검색
  
**SELECT** 속성 리스트  
**FROM** 테이블 이름 **JOIN** 테이블 이름   
**WHERE** 조건  
**GROUP BY** 속성 리스트 **HAVING** 조건  
**ORDER BY** 속성 리스트   

1\. SELECT 입력  
2\. (ALL 또는 DISTINCT 입력)  

- ALL : 투플의 중복 허용  
- DISTINCT : 투플의 중복 제거  

3\. 검색할 속성들 입력  
4\. FROM 입력  
5\. 검색하고 싶은 속성이 있는 테이블들 입력  

<br>

## **INSERT**
데이터 삽입  

**INSERT**  
**INTO** 테이블 이름[(속성 리스트)]  
**VALUES** (속성값 리스트);  

<br>

## **UPDATE**
데이터 수정  
  
**UPDATE** 테이블 이름  
**SET** 속성 이름 = 속성 값, 속성 이름 = 속성 값...  
[**WHERE** 조건];

<br>

## **DELETE**
데이터 삭제  
  
**DELETE**  
**FROM** 테이블 이름  
[**WHERE** 조건];  