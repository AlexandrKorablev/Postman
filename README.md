
___
## Запросы POST

_Создание нового юзера._
```json
http://jsonplaceholder.typicode.com/users
    {
        "id": 11,
        "name": "Alexandr Korablev",
        "username": "Alex",
        "email": "alexandr.korablev1990@mail.ru",
        "address": {
            "street": "Dimitrova",
            "suite": "Apt. 88",
            "city": "Samara",
            "zipcode": "92998-3874",
            "geo": {
                "lat": "-37.3159",
                "lng": "81.1496"
            }
        },
        "phone": "890218073**",
        "website": "https://vk.com/this_is_alex90",
        "company": {
            "name": "febest",
            "catchPhrase": "Multi-layered client-server neural-net",
            "bs": "harness real-time e-markets"
        }
```
![Создание нового юзера](https://github.com/AlexandrKorablev/Postman/blob/main/Postman%20POST%20(4).png)
___
_Размещение поста._
```json
http://jsonplaceholder.typicode.com/posts?users=11
    {
        "userId": 11,
        "id": 101,
        "title": "Создание нового поста",
        "body": "https://vk.com/this_is_alex90"
    },
```
![Размещение поста](https://github.com/AlexandrKorablev/Postman/blob/main/Postman%20POST(6).png)
___
_Добавление нового фото._
```json
http://jsonplaceholder.typicode.com/photos
    {
        "albumId": 22,
        "id": 11,
        "title": "New photo for my portfolio",
        "url": "https://via.placeholder.com/643300/92cfgc952",
        "thumbnailUrl": "https://via.placeholder.com/15550/92c952"
    },
```
![Добавление нового фото](https://github.com/AlexandrKorablev/Postman/blob/main/Postman%20POST%20(3).png)
___
## Запросы GET.

_Поиск по имени._
```json
http://jsonplaceholder.typicode.com/users?name=Mrs.Dennis Schulist
```
![Поиск по имени](https://github.com/AlexandrKorablev/Postman/blob/main/Postman%20GET%20(1).png)
___
_Поиск по номеру телефона._
```json
http://jsonplaceholder.typicode.com/users?phone=1-770-736-8031x56442
```
![Поиск по номеру телефона](https://github.com/AlexandrKorablev/Postman/blob/main/Postman%20GET%20(2).png)
___
_Поиск коментария по заголовку._
```json
http://jsonplaceholder.typicode.com/posts?title=et ea vero quia laudantium autem
```
![Поиск коментария по заголовку](https://github.com/AlexandrKorablev/Postman/blob/main/Postman%20GET%20(3).png)
___
## Запросы PATCH.

_Изменение поста._
```json
http://jsonplaceholder.typicode.com/posts/1
{
    "userId": 1,
    "id": 1,
    "title": "измененный заголовок",
    "body": "https://vk.com?this_is_alex90"
}    
```
![Изменение поста](https://github.com/AlexandrKorablev/Postman/blob/main/Postman%20PATCH.png)
___
##Запросы DELETE.

_Удаление пользователя._
```json
http://jsonplaceholder.typicode.com/users/11
```
![Удаление пользователя](https://github.com/AlexandrKorablev/Postman/blob/main/Postman%20DELETE%20.png)
