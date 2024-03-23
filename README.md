# FastAPI
## 특징
- <code>async</code> / <code>await</code> 이용한 비동기 코드 작성 가능
    ```python
    @app.get('/')
    async def read_results():
        results = await some_library()
        return results
    ```
- Swagger UI API 문서 제공
    ![Swagger UI](images/swagger_ui.png)
