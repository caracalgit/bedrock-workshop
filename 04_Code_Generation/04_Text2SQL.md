## Text2SQL : 대화로 DB를 검색하기
 
 Code Generation 을 통해 우리는 Python 과 같은 일반 프로그래밍 언어를 작성할 수 있을 뿐만 아니라 SQL 도 생성할 수 있습니다. 한 마디로 우리는 이제 대화로 DataBase를 검색할 수 있게 되었습니다. 이 섹션에서는  SQL Query Generation을 실습해 보겠습니다.




![alt text](image.png)


## 환경셋팅 

1. 다음 실습은 Calude 3 Sonnet 과 Titan Embeddings G1 - Text models를 사용하므로, model access에서 두 모델에 대한 사용 요청을 합니다. 
![alt text](image-4.png)



2. SageMaker Console(https://console.aws.amazon.com/sagemaker)을 열고 Notebook을 하나 생성합니다. 
![alt text](image-1.png)

3. Notebook Instance에서 Terminal을 실행시킵니다.  ![alt text](image-2.png)

4. 다음 코드를 clone하여 실행시킵니다. 

```
cd SageMaker
```

```
git clone https://github.com/caracalgit/natural-language-querying-of-data-in-s3-with-athena-and-generative-ai-text-to-sql.git
```

5. 노트북을 실행시키면 다음과 같습니다.

![alt text](image-3.png)
