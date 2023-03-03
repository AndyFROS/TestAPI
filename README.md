# TestAPI!
### Апи для работы с данными о погоде
![Nagatoro-Wiggle](https://user-images.githubusercontent.com/66909286/222668735-2ba056c6-6394-44b1-867b-74e5d7f6c40b.gif)


### На данный момент существует 6 методов для API
![intro](https://user-images.githubusercontent.com/66909286/222665328-18daeba4-fe2d-4cd0-9770-362b7a777f36.jpg)


## GET /WeatherForecast
Получение всех данных, присутствует необязательный параметр sortStrategy, который позволяет получить данные в отсортированном виде
![image](https://user-images.githubusercontent.com/66909286/222666172-cbee9204-f882-438f-b1ef-ec7311f0e2d0.png)
![image](https://user-images.githubusercontent.com/66909286/222666269-14ae4b78-3eb1-411b-bc9d-efcdadd24063.png)


## POST /WeatherForecast
Добавление новых записей. В качестве параметра принимает json следуюзего формата
![image](https://user-images.githubusercontent.com/66909286/222666617-12d13074-3b2c-4f6b-916a-86632f4b977d.png)


## PUT /WeatherForecast
Изминение уже существуюущих данных. В качестве параметра принимает json следуюзего формата, при этом id записи должен быть уже существующим
![image](https://user-images.githubusercontent.com/66909286/222667264-4b64587b-ac75-41d4-b703-2e24a2f9ff33.png)


## DELETE /WeatherForecast
Изминение уже существуюущих данных. В качестве параметра принимает json следуюзего формата, при этом id записи должен быть уже существующим
![image](https://user-images.githubusercontent.com/66909286/222667415-dcc08efe-cbe7-4b95-a72e-927e7d5fc0b4.png)


## GET /WeatherForecast/{id}
Получение одной записи по её id. В качетсве параметра примнимет id уже существующей записи
![image](https://user-images.githubusercontent.com/66909286/222667662-6766feac-104c-43cd-85a5-098149d3ffe3.png)


## GET /WeatherForecast/find-by-city
Получение всех записей одного города. В качестве параметра принимает строку (город)
![image](https://user-images.githubusercontent.com/66909286/222667914-d2806f27-7c93-4bee-b5bc-f661692b77c0.png)


## Схема данных
![image](https://user-images.githubusercontent.com/66909286/222668035-60628679-86b7-4264-ae16-bc4e1fa73213.png)
