# FreeGPT WebUI 
## GPT 3.5/4

<strong>NOT REQUIRE ANY API KEY</strong> ❌🔑 


Experience the power of ChatGPT with a user-friendly interface, enhanced jailbreaks, and completely free.

## Known bugs 🚧
- Stream mode not working properly.

## Note ℹ️ 
<p>
 FreeGPT - это проект, который использует различные бесплатные поставщики API для общения с искусственным интеллектом. Каждый поставщик представляет собой API, который предоставляет ответы, сгенерированные различными моделями искусственного интеллекта. Исходный код, относящийся к этим сервисам, доступен в папке G4F.

Важно отметить, что из-за широкого охвата этого проекта зарегистрированные здесь бесплатные сервисы могут получать значительное количество запросов, что может привести к временной недоступности или ограничению доступа. Поэтому часто приходится сталкиваться с тем, что эти сервисы отключены или нестабильны.

Мы рекомендуем вам искать своих собственных провайдеров и добавлять их в свои личные проекты, чтобы избежать нестабильности и недоступности сервиса. В рамках проекта, в папке Providers, вы найдете несколько примеров поставщиков, которые работали в прошлом или все еще функционируют. Легко следовать логике этих примеров, чтобы найти бесплатные сервисы GPT и включить запросы в ваш конкретный проект FreeGPT.

Пожалуйста, обратите внимание, что выбор и интеграция дополнительных поставщиков являются ответственностью пользователя и не имеют прямого отношения к проекту FreeGPT, поскольку проект служит примером того, как объединить G4F API с веб-интерфейсом.
</p>

## Table of Contents  
- [To-Do List](#to-do-list-%EF%B8%8F)  
- [Getting Started](#getting-started-white_check_mark)  
  - [Cloning the Repository](#cloning-the-repository-inbox_tray)  
  - [Install Dependencies](#install-dependencies-wrench)  
- [Running the Application](#running-the-application-rocket)  
- [Docker](#docker-)  
  - [Prerequisites](#prerequisites)  
  - [Running the Docker](#running-the-docker)
- [Incorporated Projects](#incorporated-projects-busts_in_silhouette)
  - [WebUI](#webui) 
  - [API FreeGPT](#api-g4f)
- [Star History](#star-history)
- [Legal Notice](#legal-notice) 

##

## To-Do List ✔️

- [x] Integrate the free GPT API into the WebUI
- [x] Create Docker support
- [x] Improve the Jailbreak functionality
- [x] Add the GPT-4 model
- [x] Enhance the user interface
- [ ] Check status of API Providers (online/offline)
- [ ] Enable editing and creating Jailbreaks/Roles in the WebUI
- [ ] Refactor web client

## Getting Started :white_check_mark:  
To get started with this project, you'll need to clone the repository and have [Python](https://www.python.org/downloads/) installed on your system.  
  
### Cloning the Repository :inbox_tray:
Run the following command to clone the repository:  

```
git clone 
```

### Install Dependencies :wrench: 
Navigate to the project directory:
```
cd freegpt
```

Install the dependencies:
```
pip install -r requirements.txt
```
## Running the Application :rocket:
To run the application, run the following command:
```
python run.py
```

Access the application in your browser using the URL:
```
http://127.0.0.1:1338
```
or
```
http://localhost:1338
```


