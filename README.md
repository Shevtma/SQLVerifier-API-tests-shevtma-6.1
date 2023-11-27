# SQLVerifier-API-tests-shevtma-6.1
API tests for SQLVerifier application (Postman)

Тестируемое приложение - SQLVerifier application - разворачивается локально из проекта [verifier](https://github.com/IT-switcher/verifier)

## Инструкция по загрузке из удаленного репозитория

1. Сделать fork данного репозитория
2. В **Postman** перейти во вкладку APIs
3. Выбрать **Create new API**
4. Авторизоваться в **Github** своей учетной записью
5. В Postman в поле **Github organization** выбрать свою учетную запись
6. Выбрать для подключения репозиторий `SQLVerifier-API-tests-shevtma-6.1`
7. Выбрать ветку main в качестве начальной ветки (**Initial branch**)
8. Нажать **Connect repository**
9. Переименовать **New API** согласно названию проекта
10. Загрузить из репозитория файл с переменными окружения (`SQLVerifierEnv.postman_environment.json`), затем импортировать окружение в проект локально
11. Загрузить из репозитория файл с тестовыми данными для запуска прогонов (`dataFile.csv`), выбирать этот файл перед запуском тестовых прогонов (в соответстующем разделе)
