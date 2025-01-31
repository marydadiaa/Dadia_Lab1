<h1>Laboratory Activity #1: Introduction to FastAPI</h1>
<h3>Objectives:</h3>
- Introduce FastAPI as a technology stack for developing API <br>
- Review Python as a programming language for API development <br>
- Create, run, and test APIs created using FastAPI <br>
- Practice logic building and technical expertise through coding

<h3>Instructions:</h3>
1. Create an API that will fulfill the following requirements <br>
- Written in FastAPI <br>
- Endpoint Name: /factorial/{starting_number} <br>
- Endpoint should execute the following logic: <br>
- Compute the factorial of the inputted value in the endpoint <br>
- If the value inputted is 0, the endpoint should return {"result": false} <br>
- Implement the code using a while loop <br>
<br>
2. Turn in the GitHub repository link of the code, together with dependencies needed to run the application in Google Classroom
<br>
<h3>Steps:</h3>

1. Installing dependencies like (pip install fastapi uvicorn). <br>
2. Run the API using (uvicorn main:app --reload). <br>
3. Follow this format ("GET http://127.0.0.1:8000/factorial/{starting_number}"). <br>
4. The example output for this is ("GET http://127.0.0.1:8000/factorial/1"). <br>
5. You can view it at ("Swagger UI: http://127.0.0.1:8000/docs") and
("ReDoc: http://127.0.0.1:8000/redoc") <br>

<h3>EXPECTED RESULT:</h3>

{
  "starting_number": 5, <br>
  "factorial": 120 <br>
}



